# Kw41z_Smart_Lighting

## Setup

Step 1: Install python 3.x

Step 2: Install rutime

```powershell
> python -V
Python 3.x.x

> pip -V
> pip install --user pyserial
> pip install --user django
```

Step 3: Download the FRDM-KW41Z Software Development Kit

Step 4: Click "File" in the MCUXpresso interface, select "Import" in the drop-down box

Step 5: Click "General", select "items from folders or archive files" in the drop-down box

Step 6: Click "Directory", and select the project folder "frdmkw41z_wireless_examples_thread_router_eligible_device_freertos"

Step 7: Run server

```
> cd web-serial
web-serial\ > cd source
source\ > dir
source\ > python manage.py runserver 127.0.0.