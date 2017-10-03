---
layout: archive
title: "Ubuntu 12 Installation"
date:
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
ads: false
---

Lean Emacs mode requires [Emacs](http://www.gnu.org/software/emacs/) version 24.3 (or greater).
This version is not available by default in Ubuntu 12.04. You have to execute the following commands
to install it.

{% highlight bash %}
sudo add-apt-repository ppa:cassou/emacs
sudo apt-get update
sudo apt-get install emacs24
{% endhighlight %}

Use the following commands to install Lean using PPA:

{% highlight bash %}
sudo apt-get install python-software-properties
sudo add-apt-repository ppa:ubuntu-toolchain-r/test -y
sudo add-apt-repository ppa:leanprover/lean
sudo apt-get update
sudo apt-get install lean
{% endhighlight %}

Once installed via PPA, you can use the standard `sudo apt-get upgrade` to get the latest version of Lean.

Configure the Lean Emacs mode using the instructions
available [here](https://github.com/leanprover/lean-mode).
