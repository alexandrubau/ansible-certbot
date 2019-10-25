## Certbot role

Some description for Cerbot role would be nice. Any volunteers?

### Parameters

**certbot_certificates** (type `array`, default `[]`)

Example:
```yaml
certbot_certificates:
  - name: projectname
    domains:
      - project.com
      - www.project.com
  - name: secondproject
    email: group@email.com
    domains:
      - second.com
      - www.second.com
```