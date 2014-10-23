# SSL Ping

Simple utility to ping a _HTTP_ or _HTTPS_ server. This is useful for troubleshooting intermittent network issues.

## Usage

    ssl-ping https://example.com
    
or

    ssl-ping http://example.com --ignore-errors
    
## Compiling

To compile for standalone usage on windows.

1. Install Python 2.7 for Windows (python.org)

2. Install PyWin32 extensions for Windows (sourceforge.net)

3. Install pip (https://bootstrap.pypa.io/get-pip.py)

4. Install PyInstaller

    pyinstaller -F ssl-ping.py
    
This will build a standalone .exe with the bundled `cacert.pem`.