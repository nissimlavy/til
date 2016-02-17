#Make an emergency webserver to serve up a single page
```bash
	while true; do nc -l 8080 < $filename; done;
```
