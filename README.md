# Multi-Objective-Intelligent-Academic-Timetable-Scheduling-System-By-Hybrid-Optimization-Techniques.

## Run locally

Set a strong initial admin password before the first run. In PowerShell:

```powershell
$env:ADMIN_DEFAULT_PASSWORD = "choose-a-strong-password"
python app.py
```

The password is used only when initializing an empty database. Keep it out of
source control. To run the end-to-end test, set the same environment variable
in the test terminal before running `python scripts\e2e_test.py`.