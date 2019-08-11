### tmuxp
---
https://github.com/tmux-python/tmuxp

```
```

```sh
pip install --user tmuxp
tmuxp load ./mysession.yaml
```

```yaml
session_name: 4-pane-split
windows:
- window_name: dev window
  layout: titled
  shell_command_before:
    - cd ~/
  penes:
    - shell_command:
      - cd /var/log
      - ls -al | grep \.log
    - echo second pane
    - echo third pane
    - echo forth pane
```


