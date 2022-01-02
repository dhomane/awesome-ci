## List of Continuous Integration services

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

**[Subscribe](https://github.com/ligurio/awesome-ci/subscription) to receive notificatons with updates.**

### Community

<img src="sqaunderhood-logo.svg" align="left" alt="sqaunderhood logo" width="100" style="padding: 10px;"/>

- Telegram: https://t.me/sqaunderhood
- Twitter: https://twitter.com/sqaunderhood
- Facebook: https://www.facebook.com/sqaunderhood/
- VK: https://vk.com/sqaunderhood

### Introduction

There are a lot of cloud [continuous
integration](http://en.wikipedia.org/wiki/Continuous_integration) services. All
of them have a different set of functionalities, some of them require payment, some
of them are for free. I have created a list of such
services to make an easy comparison of them and choose a more suitable one for you.

Some of the CI services have open source code thus you can set them up in standalone
mode. Pay attention to the column "Features".

There is a
[similar](https://en.wikipedia.org/wiki/Comparison_of_continuous_integration_software)
comparison on Wikipedia.

| Name | Description | Features | Supported repositories | Documentation | Price | Stars |
|------|:-------------:|:-----------:|:-------------:|:-----:|:---------:|:---:|
|[Abstruse CI](https://github.com/bleenco/abstruse) | Self-Hosted, Open-Source CI Platform. Based on NodeJS and Docker. | Languages: everything that can be installed on Linux | GitHub, GitLab, BitBucket, Gogs | [Documentation](https://github.com/bleenco/abstruse/tree/master/docs) | [Open Source](https://abstruse.bleenco.io) | [![Stars](https://img.shields.io/github/stars/bleenco/abstruse.svg)](https://github.com/bleenco/abstruse) |
|[Agola](https://agola.io) | Self-Hosted, Open Source CI/CD Platform | Languages: everything | GitHub, GitLab, Gitea | [Documentation](https://agola.io/doc/) | [Open Source](https://github.com/agola-io/agola) | [![Stars](https://img.shields.io/github/stars/agola-io/agola.svg)](https://github.com/agola-io/agola) |
|[Appcircle.io](https://appcircle.io/) | Automated mobile CI/CD/CT for iOS and Android with online device emulators. | Support for iOS (Obj-C/Swift), Android (Java/Kotlin), React Native, Flutter and Smartface | GitHub, Bitbucket, GitLab, Custom | [Documentation](http://docs.appcircle.io/) | [Free with limitations](https://appcircle.io/pricing)| |
|[App Center](https://appcenter.ms/signup?utm_source=GitHub&utm_medium=Azure) | CI Platform. It connects with Hockeyapp where you can store installers and send their by email | Compatible with Android, iOS, Xamarin, React Native, Unity, Cordova, macOS, tvOS | GitHub, BitBucket, VSTS | [Documentation](https://docs.microsoft.com/en-us/appcenter/) | [Free with limitations](https://appcenter.ms/#pricing) | |
|[Appveyor](https://ci.appveyor.com) | AppVeyor automates building, testing and deployment of .NET applications. | Languages: C#, Xamarin, F#, VB.NET, C/C++, Node.js, Ruby, TypeScript, Go, Java, Python, Perl, Erlang  | GitHub, BitBucket | [Documentation](http://www.appveyor.com/docs) | [Free with limitations](http://www.appveyor.com/pricing) | |
|[Assertible](https://assertible.com/) | Automated post-deployment testing and web service monitoring | [Example Integrations](https://github.com/assertible/deployments) | GitHub | [Documentation](https://assertible.com/docs) | [Free with limitations](https://assertible.com/plans) | |
|[AWS CodeBuild](https://aws.amazon.com/codebuild/) | Fully managed continuous integration service in AWS | Docker | AWS S3, AWS CodeCommit, Github, Bitbucket | [Documentation](https://docs.aws.amazon.com/codebuild/latest/userguide/welcome.html) | [First 100 minutes per month for free, pay-as-you-go later](https://aws.amazon.com/codebuild/pricing) |
|[Azure DevOps](https://azure.microsoft.com/en-us/services/devops/?nav=min) (formerly Visual Studio Team Services)| Cloud-based collaboration services for version control, agile planning, continuous delivery, and analytics application for Visual Studio, Eclipse, Xcode.  | | Azure DevOps, GitHub, Custom |  [Documentation](https://docs.microsoft.com/en-us/azure/devops/index?view=azure-devops) | [Free](https://visualstudio.microsoft.com/free-developer-offers/) with [monthly build limits](https://docs.microsoft.com/en-us/azure/devops/organizations/billing/buy-more-build-vs?view=azure-devops) | |
|[Bamboo](https://www.atlassian.com/software/bamboo) | Bamboo is a continuous integration and continuous deployment server | |Bitbucket (for Bitbucket Cloud), Stash (for Bitbucket Server), Git, GitHub (for GitHub and GitHub Enterprise), Mercurial, Subversion, CVS, Perforce, Custom via plugins | [Documentation](https://confluence.atlassian.com/bamboo/getting-started-with-bamboo-289277283.html?_ga=2.160145277.1739207425.1573055585-984459647.1572881977) | Full Atlassian stack for 10 users: 10$/year ( 100% of payments to charity) | |
|[BitBucket Pipelines](https://bitbucket.org/product/features/pipelines) | Bitbucket Pipelines & Deployments | [Documentation](https://bitbucket.org/product/guides/basics/four-starting-steps) | BitBucket | - | [Free with limitations](https://bitbucket.org/product/pricing) | |
|[Bitrise](http://bitrise.io/) | Mobile Continuous Integration and Delivery. | [Source code](https://github.com/bitrise-io/bitrise) is available | GitHub, BitBucket, Gitlab, Custom | [Documentation](http://devcenter.bitrise.io/) | [Free with limitations](https://www.bitrise.io/pricing)| [![Stars](https://img.shields.io/github/stars/bitrise-io/bitrise.svg)](https://github.com/bitrise-io/bitrise) |
|[Buddy](https://buddy.works) | Continuous Integration and Deployment | Languages: .NET/C#, C/C++, Clojure, Elixir, Go, Haskell, Java, Javascript, Node.JS, PHP, Python, React Native, Ruby, Scala | GitHub, Bitbucket, Gitlab, Custom | [Documentation](https://buddy.works/docs) | [Free with limitations](https://buddy.works/pricing)| |
|[builds.sr.ht](https://builds.sr.ht) | Continuous Integration services for [sourcehut](https://sourcehut.org), the hacker's forge | [open-source](https://git.sr.ht/~sircmpwn/builds.sr.ht); supports many Linux distros, BSDs and even Plan9; runs anonymous jobs that aren't tied to a repository; post-build triggers for email, webhooks, etc.; powerful API for complex build scenarios; git and mercurial support; SSH login after build failures | any supported by [dispatch.sr.ht](https://dispatch.sr.ht) (GitHub, GitLab etc.), [git.sr.ht](https://git.sr.ht), [hg.sr.ht](https://hg.sr.ht) | [Documentation](https://man.sr.ht/builds.sr.ht) | [Free and donation based ($2-$10/month) plans](https://man.sr.ht/billing-faq.md)| |
|[Buildkite](https://buildkite.com/) | A build automation platform which gives you complete control, without the pain of running your own CI system. | Languages: Ruby, Python, Node.js, JavaScript, PHP, Go, Rust, Erlang, Elixir, Java, Clojure, Scala, C/C++, Objective-C, Swift, .NET/C#<br />Source code is available: [Buildkite Agent](https://github.com/buildkite/agent) | GitHub, Bitbucket, GitLab, Custom | [Documentation](https://buildkite.com/docs/guides/getting-started) | [14-day Trial](https://buildkite.com/pricing), [Free for Education, Open Source](https://buildkite.com/pricing) | [![Stars](https://img.shields.io/github/stars/buildkite/agent.svg)](https://github.com/buildkite/agent) |
|[Chrono CI](http://www.chronoci.com/) | Continuous Integration Security | Languages: Ruby on Rails, Python, Node.js, Solidity C, Java, Go | GitHub | [Documentation](http://www.chronoci.com/docs) | [Free for 100 tests per month](http://www.chronoci.com/pricing) | |
|[Circle CI](https://circleci.com/) | Continuous Integration and Deployment | Accessing jobs via ssh, Virtualization: docker/native, OS: linux/macos/windows, ISA:several gpus/arm | GitHub, Bitbucket | [Documentation](https://circleci.com/docs) | [Free for 1 container on Linux, Windows, and Arm](https://circleci.com/pricing) |
|[Cirrus CI](https://cirrus-ci.org/) | Bring-Your-Own-Infrastructure CI with modern cloud technologies, matrix builds and simple-yet-powerful configuration | Virtualization: docker/native, OS: linux/macos/windows/freebsd, ISA:several gpus/arm | GitHub, Gitlab(community cirrus-run) | [Documentation](https://cirrus-ci.org/) | [Free for Open Source, per-second billing for private projects](https://cirrus-ci.org/pricing/) |
|[CDS](https://github.com/ovh/cds) | Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform | Languages: everything | Github, Bitbucket Server, Gitlab | [Documentation](https://ovh.github.io/cds/) | [Free Open Source](https://github.com/ovh/cds) | [![Stars](https://img.shields.io/github/stars/ovh/cds.svg)](https://github.com/ovh/cds) |
|[Codacy](https://www.codacy.com/) | Automated code reviews & code analytics | Languages: Scala, Java, JavaScript, Python, Ruby, PHP, Apex, JSP, XML, Velocity, VisualForce, C#, JSON, Kotlin, Markdown | GitHub, BitBucket | [Documentation](https://support.codacy.com/hc/en-us) | [Free for open-source projects](https://www.codacy.com/pricing) | |
|[Code Climate](https://www.codeclimate.com/) | Hosted platform to continuously measure and monitor code quality | Languages: Ruby, Javascript, PHP | GitHub, Custom | [Documentation](http://docs.codeclimate.com/) | [14-day Trial](https://codeclimate.com/pricing) | |
|[CodeFresh](https://codefresh.io/) | Codefresh is a Docker-native CI/CD platform. Instantly build, test and deploy Docker images to Kubernetes | Languages: Ruby, Python, Node.js, JavaScript, PHP, Go, Rust, Java, etc | GitHub, BitBucket, GitLab, Webhooks | [Documentation](https://docs.codefresh.io/) | [Pricing](https://codefresh.io/pricing/) | |
|[Codemagic](https://codemagic.io/) | Dedicated CI/CD for Flutter mobile, web and desktop projects. | | GitHub, BitBucket, GitLab, Custom | [Documentation](https://docs.codemagic.io/) | 500 build minutes for free each month [Pricing](https://codemagic.io/pricing/) | |
|[Codeship](https://www.codeship.io/) | One more cloud based CI service: running tests and deployment | Languages: Dart, Elixir, Go, Java and JVM based languages, PHP, Python, Node.JS, Ruby | GitHub, BitBucket | [Documentation](https://www.codeship.io/documentation) [Free ebook](http://ebooks.codeship.io/efficiency-in-development-workflows-by-codeship/) | [Free for opensource projects or 100 builds per month](https://www.codeship.io/pricing) | |
|[Concourse CI](https://concourse-ci.org/) | Self-hosted CI solution written in Golang |  | GitHub, generic oAuth | [Documentation](https://concourse-ci.org/docs.html) | Free (Open source)  | |
|[continuousphp](https://continuousphp.com/) | Continuous Integration and deployment for projects written in PHP | Languages: PHP | GitHub, BitBucket, GitLab | [Documentation](https://continuousphp.com/documentation/) | [Free for Open source and educational projects](https://continuousphp.com/plans/)  | |
|[Coveralls](https://coveralls.io) | Coveralls works with your continuous integration server to give you test coverage history and statistics. | Languages: Ruby, Javascript, Python, PHP, C, Objective-C, Scala, GO | GitHub, BitBucket | [Documentation](https://docs.coveralls.io/) | [Free for opensource projects](https://coveralls.io/pricing) | |
|[Coverity](http://www.coverity.com) | Code analysis, test analysis | Languages: C/C++, Java, C# | | None | [Free for opensource projects](http://softwareintegrity.coverity.com/free-trial-coverity.html) | |
|[Drone](https://drone.io/) | Continuous Integration service | [Source code](https://github.com/drone/drone) is available. (Community edition is licensed under Apache 2.0) | GitHub, GitLab, Gitea, BitBucket, Google Code, Custom | [Documentation](http://docs.drone.io/) | [Pricing (enterprise)](https://drone.io/enterprise/) - free self hosting - Open Source | [![Stars](https://img.shields.io/github/stars/drone/drone.svg)](https://github.com/drone/drone) |
|[Ebert](https://ebertapp.io/) | Ebert does continuous static analysis of your GitHub repositories and delivers it straight to your Pull Requests, helping your team to focus on what's important and deliver better software. | Languages: Apex, C, Clojure, CoffeeScript, CSS, Elixir, Go, Haskell, Haxe, JavaScript, Markdown, PHP, Python, Ruby, SCSS, Shell, Swift, Vim script. | GitHub | [Documentation](https://ebertapp.io/docs) | [100% free for public repositories on GitHub](https://ebertapp.io/#pricing) | |
|[Evergreen](https://github.com/evergreen-ci/evergreen) | Evergreen is a distributed continuous integration system built by MongoDB. It dynamically allocates hosts to run tasks in parallel across many machines. | | GitHub | [Documentation](https://github.com/evergreen-ci/evergreen/wiki) |  | [![Stars](https://img.shields.io/github/stars/evergreen-ci/evergreen.svg)](https://github.com/evergreen-ci/evergreen) |
|[flow.ci](https://github.com/flowci) | Self-Hosted, powerful and user-friendly CI/CD server | All Languages, Docker & K8s, High Availability, Parallel Build, Statistic | GitHub, GitLab, Gitee, Gogs | [Documentation](https://github.com/flowci/docs) | [Open Source](https://github.com/flowci/docker-install) | [![Stars](https://img.shields.io/github/stars/flowci)](https://github.com/flowci) |
|[GoCD](https://gocd.io/) | Open source, on-premises continuous delivery tool. | | Git, Perforce, Mercurial,Subversion, TFS, [Custom](https://gocd.io/plugins) | [Documentation](https://docs.gocd.io/) | [Open Source](https://gocd.io/download) | |
|[GitLab](https://about.gitlab.com/product/continuous-integration/) | GitLab is a single application for the entire DevOps lifecycle | Languages: everything that can be installed on Linux. Compatible with Linux, Windows, Android and iOS | GitLab, GitHub, Bitbucket | [Documentation](https://docs.gitlab.com/ee/ci/README.html) | [Open Source](https://about.gitlab.com/install/) plus [Free with limitations](https://about.gitlab.com/pricing/#gitlab-com) hosted version | |
|[GitGud](https://gitgud.io/) | Free & Reliable Git hosting site powered by GitLab | Everything that GitLab does but for free | GitLab, Bitbucket, GitHub, Gitea, Clone by URL | [Documentation](https://docs.gitlab.com/ee/ci/README.html) | [Completely Free](https://gitgud.io/users/sign_in) | |
|[GitHub Actions](https://github.com/features/actions) | Automate your workflow from idea to production | Workflows run in Linux, macOS, Windows, and containers on GitHub-hosted servers | GitHub | [Documentation](https://help.github.com/en/actions/automating-your-workflow-with-github-actions) | Free for Open Source and free with limits for private repositories | |
|[Hound CI](https://houndci.com/) | Hound integrates with your existing workflow by reviewing and commenting on code. | Languages: Bash, Elixir, Go, HAML, JavaScript, CoffeeScript, TypeScript, Markdown, PHP, Python, Ruby, Sass/SCSS, Swift | GitHub | | [Public repositories for free](https://houndci.com/) | |
|[Hydra](https://nixos.org/hydra/) | Nix-based continuous build system | | | [Documentation](https://nixos.org/hydra/manual/) | Opensource (GNU GPLv3) | |
|[Jenkins](https://jenkins.io/) | With thousands of plugins to choose from, Jenkins can help teams to automate any task that would otherwise put a time-consuming strain on your software team. | Languages: Embedded, PHP, Python, Ruby, Java, Android, C/C++. | Any VCS that supports git, mercurial, cvs, subversion | [Documentation](https://jenkins.io/doc/) | [Open Source](https://github.com/jenkinsci/jenkins) | [![Stars](https://img.shields.io/github/stars/jenkinsci/jenkins.svg)](https://github.com/jenkinsci/jenkins) |
|[Kraken CI](https://kraken.ci/) | Self-hosted, open source, highly scalable, focused on testing. | workflows with Starlark/Python, executors: bare metal, Docker, LXD, VM, highly scalable to thousands of executors, sophisticated test results analysis | Git, GitHub | [Documentation](https://kraken.ci/docs/) | [Open Source](https://github.com/kraken-ci/kraken) | [![Stars](https://img.shields.io/github/stars/kraken-ci/kraken)](https://github.com/kraken-ci/kraken) |
|[minci](https://github.com/kristapsdz/minci) | minimal self-hosted CI | Languages: any | |
|[Peakflow](https://www.peakflow.io/) | CI builds, error reporting and uptime monitoring | Languages: Ruby, PHP, Javascript and anything you can set up yourself. | Github | [Documentation](https://www.peakflow.io/en/faq) | [Free for private projects](https://www.peakflow.io/en) | |
|[Previs](https://github.com/PaulRosset/previs) | Use Travis configuration to run stuff locally in a clean environment. | Everything that Travis support or almost | Your computer, it's running locally! | [Documentation](https://github.com/PaulRosset/previs) | It's free! Since you are hosting everything locally on your computer! | [![Stars](https://img.shields.io/github/stars/PaulRosset/previs.svg)](https://github.com/PaulRosset/previs) |
|[Probo.CI](https://probo.ci/) | Continuous Collaboration -  break down the barriers between software developers and the other stakeholders involved in a software development project | Underlying engine is OSS, offers several Ubuntu base images, asset pre-upload helps build speed. | GitHub, BitBucket | [Documentation](https://docs.probo.ci/) | 2 month free trial then starts at $30. [Pricing](https://probo.ci/pricing/) | |
|[RazorOps](https://razorops.com/) | RazorOps is a Container-Native CI/CD platform. Instantly build, test and deploy Docker images to Kubernetes | Languages: Docker, Ruby, Python, Node.js, JavaScript, PHP, Go, Rust, Java, etc | GitHub, BitBucket, GitLab, Webhooks | [Documentation](https://docs.razorops.com/) | [Pricing - Free for Open Source, Free plan with limitations](https://razorops.com/pricing/) | |
|[Saucelabs](https://saucelabs.com/) | Automated testing in the cloud for CI | | | [Documentation](https://docs.saucelabs.com/) | [14-day Trial](https://saucelabs.com/pricing) | |
|[Scrutinizer](https://scrutinizer-ci.com/) | Build quality software, better | [Sources](https://github.com/scrutinizer-ci) are available | GitHub, BitBucket | [Documentation](https://scrutinizer-ci.com/docs/) | [14-day Trial](https://scrutinizer-ci.com/pricing) | [![Stars](https://img.shields.io/github/stars/scrutinizer-ci/scrutinizer.svg)](https://github.com/scrutinizer-ci/scrutinizer) |
|[Semaphore](https://semaphoreci.com/) | Hosted continuous integration and delivery solution for open source and private projects. | Ruby, Node.js, JavaScript, Go, Clojure, Elixir, Erlang, Java, PHP, Scala, C/C++  | GitHub, BitBucket | [Documentation](https://docs.semaphoreci.com/) | [Free for Open Source, pay only for what you use, first $20 every month on Semaphore (up to 1,300 service minutes)](https://semaphoreci.com/pricing) | |
|[Shippable](https://www.shippable.com/) | Continuous Delivery | Languages: Ruby, Python, Java, Node.js, Scala, PHP, Go; Databases: MongoDB, MySQL, Redis, Postgres, CouchDB, RethinkDB, Neo4j, and SQLite | GitHub, BitBucket, GitLab | [Documentation](http://docs.shippable.com/) | [Free with limitations](https://www.shippable.com/pricing.html) | |
|[Sider](https://sider.review/) | Increase code review efficiency and deliver products with confidence. Sider helps development teams accomplish more, allowing them to deliver more value to their customers. | [Supported Analysis Tools](https://sider.review/en/features/tools) | GitHub | [Documentation](https://help.sider.review/) | [Free 14-day trial for private repositories, and forever free for open source](https://sider.review/pricing) | |
|[Snake CI](https://snake-ci.com/) | On-premise (self-hosted) CI/CD for Bitbucket Server & DataCenter | Languages: everything; Docker; [Runner source code](https://github.com/reconquest/snake-runner); Native Bitbucket UI; Self-hosted; Config in YAML | Bitbucket Server & DataCenter | [Documentation](https://snake-ci.com/docs/) | [30-days trial](https://snake-ci.com/pricing/) |
|[SonarQube](https://www.sonarqube.org/) | "Thousands of automated Static Code Analysis rules, protecting your app on multiple fronts" | 29 Languages: Java, Kotlin, C#, VB.NET, C, C++, JavaScript, TypeScript, php, Python, Terraform, CloudFormation, ABAP, Apex, COBOL, CSS, Flex, Go, HTML, Objective-C, PL/I, PL/SQL, RPG, Ruby, Scala, Swift, T-SQL, VB6, XML | GitHub, Azure DevOps, Bitbucket, GitLab, Docker Support, Your IDE | [Documentation](https://docs.sonarqube.org/latest/) | [Free - with upgrade options](https://www.sonarqube.org/downloads/) | [![Stars](https://img.shields.io/github/stars/bleenco/abstruse.svg)](https://github.com/SonarSource/sonarqube/) |
|[StyleCI](https://styleci.io/) | The Web Coding Style Service, used by [Cachet](https://cachethq.io/) and [Laravel](https://laravel.com/). | Languages: PHP, JavaScript, TypeScript, Flow, CSS, SCSS, Less, Vue.js, Python | GitHub, BitBucket, GitLab | [Documentation](https://docs.styleci.io/) | [Free for opensource projects](https://styleci.io) | |
|[SurplusCI](https://surplusci.com/) | Affordable dedicated runners for your CI pipeline builds, usable with your current CI platform. | Languages: PHP, JavaScript, TypeScript, Flow, CSS, SCSS, Less, Vue.js, Python | GitHub, GitLab | [Documentation](https://surplusci/) | [Free trial runner & runners start at $12/month](https://surplusci.com) | |
|[TeamCity](https://www.jetbrains.com/teamcity/) | A Java-based build management and continuous integration server from JetBrains. | Support [wide variety of web browsers and build tools](https://confluence.jetbrains.com/display/TCD10/Supported+Platforms+and+Environments#SupportedPlatformsandEnvironments-BuildRunners) | Git, Subversion, Perforce, Team Foundation Server, Mercurial, CVS, SourceGear Vault 6 and 7, Borland StarTeam 6 and up, IBM Rational ClearCase, Base and UCM modes, Microsoft Visual SourceSafe 6 and 2005 | [Documentation](https://confluence.jetbrains.com/display/TCD10/TeamCity+Documentation) | [Free with limitations](https://www.jetbrains.com/teamcity/buy/#license-type=new-license) | |
|[Travis CI](https://travis-ci.org/) | Hosted continuous integration service for open source and private projects. | Languages: C, C++, Clojure, D, Erlang, Go, Groovy, Haskell, Java, Javascript (with Node.js), Objective-C, Perl, PHP, Python, Ruby, Rust, Scala. [Source code](https://github.com/travis-ci/travis-ci) is available. | GitHub | [Documentation](http://docs.travis-ci.com/user/getting-started/) | [Pricing](https://travis-ci.com/pricing) | |
|[Thundra Foresight](https://thundra.io/foresight) | A visibility tool into CI pipelines by spotting test failures in no time. | Languages: Java | GitHub, TeamCity, Bitbucket, Gitlab, Jenkins, CircleCI, TravisCI | [Documentation](https://foresight.docs.thundra.io/) | Free | |
|[Wercker](https://app.wercker.com) | Continuous delivery platform | | Docker Hub | [Documentation](https://devcenter.wercker.com/) | | | |
|[Woodpecker](https://woodpecker.laszlo.cloud/) | Continuous Integration service | Woodpecker is a community fork of the [Drone CI](https://github.com/drone) system. | GitHub, GitLab, Gitea, BitBucket, Custom | [Documentation](https://woodpecker-ci.github.io/docs/intro) | Free Open Source (Apache License 2.0) | [![Stars](https://img.shields.io/github/stars/laszlocph/woodpecker.svg)](https://github.com/laszlocph/woodpecker/) |
|[Zuul](https://zuul-ci.org) | A Project Gating System | Self-Hosted, Open Source CI/CD Platform, Gating | GitHub, Gerrit, Pagure | [Documentation](https://zuul-ci.org/docs/zuul) | [Open Source](https://zuul-ci.org) | |



### License

[![CC0 Public Domain](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sergey Bronnikov](https://bronevichok.ru) has
waived all copyright and related or neighboring rights to this work.
