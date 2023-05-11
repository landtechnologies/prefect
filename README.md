## LandTech Prefect Cloud Setup

The following action installs and authenticates to Prefect 2 cloud

## How to 
Add the following lines to your GitHub workflow:
```yaml
- name: install prefect
uses: landtechnologies/prefect@v3.0.0
with:
  prefect-api-key: <INSERT API KEY>
```