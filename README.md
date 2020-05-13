# Alfred-Workflows

VPNManager is a pure bash script filter for connecting/disconnecting native MacOS VPN adapters.  No arguments needed, it will discover VPN adapters after entering the keyword "VPN".  Currently only supports connecting a single adapter at a time.  If a connection is active it will give you the option to disconnect.
It uses scutil to retrieve and manage connections so it works with Cisco IPSec connections that AppleScript does not.
