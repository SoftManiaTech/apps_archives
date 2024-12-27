```bash
[source::http:keycloak]
SEDCMD = s/(?ms)\"kubernetes_annotations\":.*\},|(?ms)\"kubernetes_labels\":.*\},|(?ms)\"kubernetes_container_hash\":.*?,|(?ms)\"kubernetes_docker_id\":.*?,|(?ms)\"kubernetes_container_image\":.*"//g
```
