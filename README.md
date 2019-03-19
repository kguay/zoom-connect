<img src="https://raw.github.com/kguay/zoom-connect/master/zoomconnect.svg?sanitize=true" height="90px">

[![Build Status](https://travis-ci.org/cafe-code/cafecode.io.svg?branch=master)](https://travis-ci.org/cafe-code/cafecode.io)

*A new way to connect to Zoom meetings.*

Built using Hugo (gohugo.io), ZoomConnect is a static tool that allows users to easily schedule and connect to Zoom meetings. ZoomConnect works best with Zoom Rooms and organizational accounts that use a "personal" (fixed) Meeting ID for all meetings (vs. dynamic Meeting IDs that are different for each meeting).

## Zoom configuration
ZoomConnect works under a few assumptions that might not be true for all organizations. First, "personal" Meeting ID's should be used instead of dynamic Meeting ID's. Personal ID's are static and do not change from meeting to meeting. Each account/Zoom Room is asigned one and they can easily be changed (e.g. to match a company's phone number scheme).
