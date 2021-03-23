---
layout: post
title: Keep your OS Python environment clean with virtualenv
description: Short guide how to install and use virtualenv
img: python.png #side note best fitting size is probably 1280x850
fig-caption: virtualenv
tags: [python, virtualenv, virtual environments, dev, devops]
comments: true
categories: Python
---

As Cloud Engineer I am working with Python and from time to time scripts/apps can require different Python versions or use many different dependencies. This can lead to some mess if I would like to do all those Python things on my OS. But have no fear - this is where virtualenv comes into play. Thanks to that neat tool we can create isolated Python environments for our projects/applications without messing with each project environment. Installation and usage are VERY simple so let's go through it, shall we?

# Installation
This couldnt be easier:
```pip install virtualenv```

# Creating virtualenv
Now we need directory for our virtualenvs, it can be anywhere but i prefer to have one dir with all my virtual environments so in my example:  
`mkdir venvs`  
`cd venvs`   
Next create environment  
`virtualenv NAME_OF_ENVIRONMENT`

# Usage
now everything we need is just to activate our virtual environment
`source NAME_OF_ENVIRONMENT/bin/activate`

