# Contributing to OpenSearch Plugins
Depending on the plugin relationship with the OpenSearch organization we currently recommend the following naming conventions and optional follow-up checks:

### Official plugins

For the **official plugins** that live within the OpenSearch organization (i.e. they are included in [OpenSearch/plugins/](https://github.com/opensearch-project/OpenSearch/tree/main/plugins) or [OpenSearch/modules/](https://github.com/opensearch-project/OpenSearch/tree/main/modules) folder), and **which share the same release cycle as OpenSearch** itself:

- Do not include the word `plugin` in the repo name (e.g. [job-scheduler](https://github.com/opensearch-project/job-scheduler))
- Use lowercase repo names
- Use spinal case for repo names (e.g. [job-scheduler](https://github.com/opensearch-project/job-scheduler))
- Do not include the word `OpenSearch` or `OpenSearch Dashboards` in the repo name
- Provide a meaningful description, e.g. `An OpenSearch Dashboards plugin to perform real-time and historical anomaly detection on OpenSearch data`.

### Thirdparty plugins

For the **3rd party plugins** that are maintained as independent projects in separate GitHub repositories **with their own release cycles** the recommended naming convention should follow the same rules as official plugins with some exceptions and few follow-up checks:

- Inclusion of the words like `OpenSearch` or `OpenSearch Dashboard` (and in reasonable cases even `plugin`) are welcome because they can increase the chance of discoverability of the repository
- Check the plugin versioning policy is documented and help users know which versions of the plugin are compatible and recommended for specific versions of OpenSearch 
- Review [CONTRIBUTING.md](CONTRIBUTING.md) document which is by default tailored to the needs of Amazon Web Services developer teams. You might want to update or further customize specific parts related to:
  - **Code of Conduct** (if you do not already have CoC policy then there are several options to start with, such as [Contributor Covenant](https://www.contributor-covenant.org/)),
  - **Security Policy** (you should let users know how they can safely report security vulnerabilities),
  - Check if you need explicit part about **Trademarks and Attributions** (if you use any registered or non-registered trademarks we recommend following applicable "trademark-use" documents provided by respective trademark owners)
