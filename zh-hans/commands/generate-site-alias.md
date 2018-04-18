# generate:site:alias
Generates a site alias.

**使用方法:**
```
drupal generate:site:alias [options]
gsa
```

## 可用选项
选项 | 详细信息
-------|-------------
--site | Use local site as destination.
--name | Site name.
--environment | Environment name.
--type | The site type.
--composer-root | The Drupal root project directory.
--site-uri | Drupal uri (for multi-sites).
--host | The ip/domain name of the remote system. Not required on local sites.
--user | The username to use when connecting via ssh.
--port | The port to use when connecting via ssh.
--extra-options | Used only when the target requires extra options, such as alternative authentication method and/or alternative identity file.
--directory | Directory to store the generated site alias.