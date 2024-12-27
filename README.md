```bash
[source::http:keycloak]
DATETIME_CONFIG = 
INDEXED_EXTRACTIONS = none
KV_MODE = json
LINE_BREAKER = ([\r\n]+)
NO_BINARY_CHECK = true
SEDCMD = s/(?ms)\"kubernetes_annotations\":.*\},|(?ms)\"kubernetes_labels\":.*\},|(?ms)\"kubernetes_container_hash\":.*?,|(?ms)\"kubernetes_docker_id\":.*?,|(?ms)\"kubernetes_container_image\":.*"//g
category = Structured
description = JavaScript Object Notation format. For more information, visit http://json.org/
disabled = false
pulldown_type = 1
```





