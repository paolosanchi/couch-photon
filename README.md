# couch-photon
CouchDB admin tool, modernized Futon. Early beta, but what is clickable essentially works. 

May hang IE Edge. Tested very superficially since work is in progress.

## Install
Download `photon.json`, and use one of the following ways:

a) Open JSON in any text editor. Create a doc in any CouchDB bucket, copy-paste JSON text into it. Save. Run `index.html`.

b) `curl -H 'Content-Type: application/json' -X PUT http://yourdomain.com:5984/somedb/_design/photon -d @photon.json`. Run `index.html`.

Next time you can upgrade Photon directly from Photon, copy-pasting updates to design doc.
