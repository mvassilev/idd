# Introduction

IDD is a tool for performing interactive dynamic differential debugging capable to identify functional and performance regressions.

##  :beginner: About

IDD loads two versions of the same application. The first one is the base version that works as expected while the second version of the same program has a regression introduced. IDD inspects the two versions of the applications using external tools like gdb and lldb. The two applications are executed side by side and the user is allowed to dispatch commands to the underlying debuggers in order to expect their internal states and isolate the origin of the regression.

## :zap: Usage
Write about how to use this project.
`python3 idd.py -c gdb -ba <path to base executable> -ra <path to regressed executable>`

###  :electric_plug: Installation
- Steps on how to install this project on Ubuntu 22.04

-- Creating new environment:
```
$ python3 -m venv iddenv
$ source iddenv/bin/activate
```


-- Installing required packages:
```
$ pip3 install textual textual_inputs pygdbmi
```

## :cherry_blossom: Community

Join our discord for discussions and collaboration.

<a target="_blank" href="https://discord.gg/Vkv3ne4zVK"><img src="images/discord.svg" /></a>


 ###  :fire: Contribution

 Your contributions are always welcome and appreciated. Following are the things you can do to contribute to this project.

 1. **Report a bug** <br>
 If you think you have encountered a bug, and I should know about it, feel free to report it [here](https://github.com/compiler-research/idd/issues) and we could take care of it.

 2. **Request a feature** <br>
 You can also request for a feature [here](https://github.com/compiler-research/idd/issues), and if it will viable, it will be picked for development.  

 3. **Create a pull request** <br>
 It can't get better then this, your pull request will be appreciated by the community. You can get started by picking up any open issues from [here]() and make a pull request.

 > If you are new to open-source, make sure to check read more about it [here](https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source) and learn more about creating a pull request [here](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github).

## Issues

1. Make panels scrollable
2. Make panels configurable
3. Support entering commands to a specific analyzer.
