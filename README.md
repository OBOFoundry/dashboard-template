# Template repository to create Custom OBO Foundry Dashboard

Custom configuration at `dashboard-config.yml`

```yaml
...
ontologies:
  custom:
    - id: Ontology id
      mirror_from: Link to the OWL file in your repository.
      title: Ontology's title
      contact: 
        email: 
        label: 
        orcid: 
        github: 
      description: Ontology's description
      domain: Ontology's domain
      homepage: Ontology's page
      products:
        - id: 
      dependencies:
        - id: 
      tracker: Link to ontology's issue tracker
      license:
        url: License's url
        label: License's label
      preferredPrefix:
      base_ns: Base namespaces
```
