# Version Leak

```
step1. go to the target says- https://redacted.com
step2. open view page source
step3. check for path, directories
step4. go that path says- https://redacted.com/theme/css/file.css
step5. try to visit all directories and check it is accessible or not.
step5. if it is give 403
step6. add %0, %m, %2e, says- https://redacted.com/%0theme and then check the response, it will show the running server name, and version information.
```
- And check for also css path url, sometime it contain some path.
