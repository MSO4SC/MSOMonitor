# MSOMonitor Docker image

## Usage

```
# docker run -p 9090:9090 mso4sc/monitor
time="2017-10-03T15:16:46Z" level=info msg="Starting prometheus (version=1.7.2, branch=HEAD, revision=22eadbe635528fa17b99a7635fed6b6018103042)" source="main.go:88"
time="2017-10-03T15:16:46Z" level=info msg="Build context (go=go1.8.3, user=root@05b1548df2cc, date=20170926-16:41:43)" source="main.go:89"
time="2017-10-03T15:16:46Z" level=info msg="Host details (Linux 4.4.0-96-generic #119-Ubuntu SMP Tue Sep 12 14:59:54 UTC 2017 x86_64 ef32ca09e862 (none))" source="main.go:90"
time="2017-10-03T15:16:46Z" level=info msg="Loading configuration file /etc/prometheus/prometheus.yml" source="main.go:252"
time="2017-10-03T15:16:46Z" level=info msg="Loading series map and head chunks..." source="storage.go:428"
time="2017-10-03T15:16:46Z" level=info msg="0 series loaded." source="storage.go:439"
time="2017-10-03T15:16:46Z" level=info msg="Listening on :9090" source="web.go:259"
time="2017-10-03T15:16:46Z" level=info msg="Starting target manager..." source="targetmanager.go:63"
```


One script helps working with docker:  
`run.sh` runs a new monitor in a new container.  

To build the image locally, `build.sh` helps doing it.  
