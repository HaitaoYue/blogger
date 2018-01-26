---
title: How to squash remote commits
date: 2018-01-26 13:35:31
description: When you create multi commits for pull request, how to squash multi remote commits?
categories: git
tags: [git] 
toc: 
feature: 
---

# How to squash multi commits into one when create pull request

First look at our commits history:
{% codeblock %}

commit 2ddba7901d938320adfcd97dd87a24e4a1b92dd8 (HEAD -> master)
Author: Haitao Yue <hightall@me.com>
Date:   Fri Jan 26 13:39:00 2018 +0800

    add 3

commit 2e70f1c39485cd9cc984174524080861a89aa0a5
Author: Haitao Yue <hightall@me.com>
Date:   Fri Jan 26 13:38:48 2018 +0800

    add 2

commit ae23695ffaef45ac1d10509f6e273fe8ac732db7
Author: Haitao Yue <hightall@me.com>
Date:   Fri Jan 26 13:38:37 2018 +0800

    init
{% endcodeblock %}

If you want to squash these two commits.

{% codeblock %}
git rebase -i HEAD~2
{% endcodeblock %}

will squash 2 commits recently. Then will pick or squash commit in edit mode.

{% asset_img pick.png pick or squash commits %}

After you save, then will see the message edit.

{% asset_img edit.png edit message %}

Then push the commits to remote git, use force mode.

{% codeblock %}
git push -f
{% endcodeblock %}
