## Runtime events

```bash
curl --request GET \
  --url https://demoeu-instana.instana.io/api/events \
  --header 'authorization: apiToken <token>'
```

```bash
curl --request GET \
  --url https://ibmdevsandbox-instanaibm.instana.io/api/events \
  --header 'authorization: apiToken <token>'
```

```bash
curl --request GET \
  --url https://test-instana.pink.instana.rocks/api/events \
  --header 'authorization: apiToken <token>'
```


## Built-in events

```bash
curl --request GET \
  --url https://demoeu-instana.instana.io/api/events/settings/event-specifications/built-in \
  --header 'authorization: apiToken <token>'
```

```bash
curl --request GET \
  --url https://ibmdevsandbox-instanaibm.instana.io/api/events/settings/event-specifications/built-in \
  --header 'authorization: apiToken <token>'
```
