DevOps始于"[敏捷系统管理](https://blog.newrelic.com/2014/05/16/devops-name/)"一文。 2008年, [安德鲁（Andrew Shafer）](https://twitter.com/littleidea)发表了["敏捷基础（Agile Infrastucture）"](http://www.jedi.be/blog/2008/10/09/agile-2008-toronto-agile-infrastructure-and-operations-presentation/) 的演讲，意图解决许多开发者和公司遇到的类似问题。

2009年，[帕特里克（Patrick Debois）](https://twitter.com/patrickdebois)创立了"DevOpsDays"会议来推广DevOps的概念。然而，直到谷歌发布[2010年趋势盘点](https://trends.google.co.uk/trends/explore?date=all&q=devops)一文后，人们才开始把DevOps当成一项[独立的概念](http://www.somic.org/2010/03/02/the-rise-of-devops/)。

如今，DevOps的概念已经不止于开发、系统管理和基础，它包括[开发、运维、敏捷、云、开源和商业化](https://blogs.the451group.com/opensource/2010/03/03/devops-mixing-dev-ops-agile-cloud-open-source-and-business/)等等。

DevOps在不断演变。目前，DevOps[不存在认证、角色、系列工具或是固定流程](https://sites.google.com/a/jezhumble.net/devops-manifesto/)。没有规范，也不是一个产品或是职位的名称。没有一种权威的说法能定义DevOps是什么或不是什么。它关乎于态度、思想、习惯、行为、文化、范式、哲学。它是一种思考、行动、存在的方式。实践就是最好的布道。践行DevOps是一场对话，你将采取最佳的方式实践并将经验分享给他人。

以下有一些已经被验证有效的非常重要的质量标准、指导原则、技术要点，每个人都应该了解。从它们开始实践DevOps会是最好的尝试。

开始学习吧！

<!--more-->

_注：以下实践准则已经按它们最合适出现的阶段划分，以望读者能更容易地理解……虽然并不能保证这种划分一定准确。_

## 从瀑布模型到敏捷流程

- [人才是关键](https://techbeacon.com/psychology-devops-understanding-people-key-success) - 一开始就把所有人聚集在一起起。保持站会。 让每个人都能更轻易地知道发生了什么。
- [是产品而不是项目](https://www.madetech.com/blog/products-not-projects) - 交付团队从软件上线到下线，运转的是软件产品而不是项目。
- [每件事都要做版本控制](https://www.ibm.com/developerworks/library/a-devops6/index.html), 所有的代码都应该处在版本控制下，以便能够进行代码开发、评审，以及能应用于源代码管理工具和代码合并。
- [文化](https://martinfowler.com/bliki/DevOpsCulture.html) - 这里有[T恤](https://www.redbubble.com/shop/devops+t-shirts), [歌曲](https://www.youtube.com/watch?v=pebIr4F-vjQ), [MV](https://www.youtube.com/watch?v=iYLxw6OsZug), [广播](http://devopscafe.org/), [书籍](https://medium.com/devopslinks/10-great-books-for-aspiring-devops-sre-engineers-76536c7c4909). DevOps的文化传播与实践一样重要。
- [看板](http://blog.crisp.se/mattiasskarin/files/slides/introducing_kanban_in_operations.pdf) - 能够将工作流限制在给定的工人上是很关键的，你必须限制在制品数量。
- [域驱动设计](https://www.thoughtworks.com/insights/blog/domain-driven-design-services-architecture)
- [系统类比](https://en.wikibooks.org/wiki/Software_Engineering_with_an_Agile_Development_Framework/Iteration_One/System_metaphor)
- [系统化思考](https://en.wikipedia.org/wiki/Systems_theory)
- [最多能吃两个披萨的队伍](http://blog.idonethis.com/two-pizza-team/)
- [优先级 - 最先处理最重要的事](http://www.theagilemindset.co.uk/the-scrum-philosophy/)
- [使用类比来讨论重要概念](http://www.techrepublic.com/blog/10-things/10-ways-to-explain-things-more-effectively/)
- [无罪化的后遗症](https://codeascraft.com/2012/05/22/blameless-postmortems/)
- [提早发布，频繁发布](http://www.catb.org/esr/writings/homesteading/cathedral-bazaar/ar01s04.html) - 在代码进入生产环境前，实际上没产生任何价值。[如果这样做很痛苦，请更要经常做](https://martinfowler.com/bliki/FrequencyReducesDifficulty.html)，提前去经历它。
- 频繁发布 - [如何吃掉一头大象 - 一次咬一口](https://www.linkedin.com/pulse/how-eat-elephant-one-bite-time-asia-shahzad/)
- 聆听消费者的需求。 - 形成闭环，专注于构建人们想要使用的伟大产品。
- [举例说明](https://www.thoughtworks.com/insights/blog/specification-example)
- [守-破-离](https://martinfowler.com/bliki/ShuHaRi.html) - 遵守规则，打破规则，演化规则。
- [牺牲性建筑](https://martinfowler.com/bliki/SacrificialArchitecture.html)
- [拥抱失败](https://www.thebalance.com/steve-jobs-and-how-embracing-failure-saved-apple-1200640)
- [适用于康威定律](https://haacked.com/archive/2013/05/13/applying-conways-law.aspx/)

## 从敏捷到精益

- [Continuous Improvement](https://en.wikipedia.org/wiki/Kaizen) - An “improvement,” or “change for the better” which refers to a philosophy or practices that focus on continuous improvement of processes in manufacturing, engineering, game development, and business management.
- [Reduce waste](https://itrevolution.com/japanese-words-for-devops-practitioners/)
- [No silos](https://continuousdelivery.com/2012/10/theres-no-such-thing-as-a-devops-team/) - Cross-functional teams and T-shaped people, an attitude of shared responsibility is an aspect of DevOps culture that encourages closer [collaboration](https://blog.chef.io/2017/03/01/devops-is-all-about-collaboration/).
- [Key Performance Indicators](https://www.atlassian.com/devops#measurement) - Management thinker Peter Drucker is often quoted as saying that "you can't improve what you can't measure".
- [Non-Functional Requirements as user stories](https://legacy.devopsdays.org/blog/wp-content/uploads/2010/02/rachel-davies-nonfunctional-devopsdays.pdf)
- [Minimum viable product](http://blog.crisp.se/2016/01/25/henrikkniberg/making-sense-of-mvp)
- [A journey, not a destination](https://notafactoryanymore.com/2015/08/14/a-personal-devops-journey-or-a-never-ending-journey-to-mastery/)
- [Embrace change](https://www.theregister.co.uk/2016/01/15/devops_people_problem/)
- [Build the right thing, then build it the right way](https://barryoreilly.com/2016/10/06/10-principles-to-transform/)
- [Lean startup](http://ecorner.stanford.edu/videos/2329/Evangelizing-for-the-Lean-Startup-Entire-Talk)
- [People over process](https://jezhumble.net/2007/09/11/line-management.html)
- [Test at the appropriate level](https://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid)
- [High trust culture](https://gotocon.com/dl/goto-cph-sept-2014/slides/JezHumble_LeanEnterprisePartII.pdf)
- [Address Technical Debt](https://18f.gsa.gov/2015/09/04/what-is-technical-debt/)

## 从精益到持续集成

- ["cattle rather than pets"](https://www.theregister.co.uk/2013/03/18/servers_pets_or_cattle_cern/) - the paradigm of disposable server infrastructure.
- [Achieving 10 deployments per day](https://www.youtube.com/watch?v=LdOe18KhtT4) - the story of how Flickr adopted DevOps.
- [Continuous Integration](https://martinfowler.com/bliki/ContinuousIntegrationCertification.html) - When the build fails, it’s usually back to green within ten minutes.
- [Quality Built In](https://www.slideshare.net/AndrewDzynia/quality-built-in/) - Build quality in, from start to end. Quality is not something you tack on the end.
- [Zero Bugs](http://schd.ws/hosted_files/aatc2017/c9/Zero%20Bugs.pdf)
- [Don't fire the QA](https://www.thoughtworks.com/insights/blog/qa-role-what-it-really) - Are we building the correct product? If so, are we building it correctly?
- [Automation](https://dzone.com/articles/what-is-devops-and-how-automation-helps-achieve-it)
- [Test Automation](https://www.atlassian.com/blog/devops/test-automation-secret-devops-success)
- [Automation over documentation](https://githubengineering.com/runnable-documentation/)
- [Shift left](https://dzone.com/articles/the-shift-left-principle-and-devops-1)
- [Testing as code](http://www.bbc.co.uk/blogs/internet/entries/ff14236d-098a-3565-b678-ff4ba5776a5f) - Use the gherkin language "[Business Readable, Domain Specific Language](https://martinfowler.com/bliki/BusinessReadableDSL.html)", for manual as well as automated. Keep all your tests with your code, use version control to track changes.

## 从持续集成到持续交付

- [Continuous Delivery](https://techbeacon.com/agile-devops-continuous-delivery-evolution-software-delivery) - Continuous Delivery is a key part of the evolution of adopting a DevOps culture.
- [Deployment Pipelines](https://continuousdelivery.com/implementing/patterns/) - Get humans out of the deployment business. Create a repeatable, reliable process for releasing software.
- [Trunk based Development](https://www.thoughtworks.com/insights/blog/enabling-trunk-based-development-deployment-pipelines) - Moving to trunk-based development is an ([essential step in getting to continuous deployment](https://engineering.moonpig.com/development/move-to-trunk-based-development-without-the-chaos)).
- [Production-ready software](https://www.slideshare.net/jezhumble/devops-and-agile-release-management) - Fast, automated feedback on the production readiness of your applications every time there is a change - to code, infrastructure, or configuration.
- [Everything as code](https://www.slideshare.net/dubsquared/eac-25454047) - Infrastructure as Code, Security as Code, Compliance as Code, Testing as Code.
- [Reduce the risk of releasing](http://slidesha.re/dsSZIr)
- [Automate (almost) everything](https://www.thoughtworks.com/insights/blog/automate-almost-everything)
- [Securing Software through Continuous Delivery](https://www.oreilly.com/learning/devopssec-securing-software-through-continuous-delivery)
- [Focus on mean time to recovery](https://www.thoughtworks.com/radar/techniques/focus-on-mean-time-to-recovery)
- [Pipelines as code](http://inedo.com/blog/pipelines-as-code-how-you-can-fully-embrace-agile-and-devops)
- [Decrease lead time](https://techbeacon.com/doing-continuous-delivery-focus-first-reducing-release-cycle-times)

## 从持续交付到持续部署

- [Feature Toggles](https://martinfowler.com/bliki/FeatureToggle.html) rather than feature branches, avoiding merge hell and more control over features and deployments.
- [Infrastructure as Code](https://stochasticresonance.wordpress.com/2009/07/12/infrastructure-renaissance/) - Using orchestration and provisioning tools such as Terraform, Docker, Kubernetes, Ansible, Chef, Puppet.
- [Done means released](https://blog.codecentric.de/en/2010/10/devopsdays-in-hamburg-%E2%80%9Cdone%E2%80%9D-means-released/)
- [Everybody is responsible for delivery](http://blog.macisaacconsulting.com/continuous-delivery-everybody-responsible-quality/)

## 从持续部署到持续运维

- [Blue Green Deployments](https://martinfowler.com/bliki/BlueGreenDeployment.html)
- [Put devs on call](https://victorops.com/putting-devs-on-call/) - Developers are responsible for monitoring and alerting
- [High Scalability](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)
- [Moving from Monoliths to Microservices](https://gotocon.com/amsterdam-2016/presentation/Journey%20from%20Monolith%20to%20Microservices%20and%20DevOps)
- [Data-driven products](https://medium.com/@neal_lathia/what-do-we-mean-when-we-talk-about-data-driven-products-127ceb3e6cf)
- [Performance testing as a first-class citizen](https://internetperformanceexpert.com/2013/09/26/treat-performance-as-a-first-class-citizen/)
- [Embrace NoSQL](https://diginomica.com/category/devops-stack/)
- [Immutable infrastructure](https://dzone.com/articles/why-you-should-build-immutable)
- [Big data](http://blog.syncsort.com/2017/04/big-data/big-data-and-devops/)
- [Platform as a service](https://blogs.msdn.microsoft.com/brunoterkaly/2014/04/17/the-devops-story-why-it-is-really-about-platform-as-a-service/)
- [Cloud](https://www.infoq.com/articles/cloud-and-devops)
- [Design for failure](https://martinfowler.com/articles/microservices.html#DesignForFailure)
