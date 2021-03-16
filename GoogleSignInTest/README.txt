Instructions on how to run server:

1. Navigate to C:\ using 'cd\'
2. If not already, install http-server w/ npm install --global http-server
3. Navigate to file where index.html is stored using dir and cd\"filename"
4. Run server with 'http-server -o -a localhost'

Common errors include:
1. Running with https-server instead of http-server
2. Not adding OAuth privledges to website with Google OpenID
3. Running server without '-a localhost' to set IP address name for OpenID