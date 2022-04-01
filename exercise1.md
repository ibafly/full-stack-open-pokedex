# 11.1 Warming up

- for Java:
	- linting: NetBeans IDE, Eclipse, Android Studio, SpotBugs, VS Code with extentions SonarLint/Checkstyle
	- testing: JUnit, Spock Framework
	- building: Maven, Ant, Gradle with Java plugin

- CI alternatives, [see also](https://github.com/ligurio/awesome-ci):
	- self-hosted: TeamCity, Drone.io, Bamboo, Abstruse CI, Agola, Concourse CI, flow.ci, Kraken CI, minci, Zuul
	- cloud-based: Gitlab, Bitbucket, Jenkins X, Tekton, TeamCity Cloud, AWS CodePipeline, GCP, Azure Pipelines, Cirrus CI, Codeship, Saucelabs

- Under the situation: a team of around 6 people & app in active deployment and will be released soon. It is better to do CI setup in a cloud-based environment than self-hosted. Because the team is small, the project is young, the configuration is simple at first and the expense is low.

