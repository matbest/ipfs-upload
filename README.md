# ipfs-upload
A Simple webpage to upload files to the ipfs

1. Run ipfs
> $ ipfs daemon
2. Run an HTML server serving up the index.html found in this repo
> $ http-server -p 1337
3. Visit local webpage
> http://127.0.0.1:1337
4. Upload File

Source for this came from : https://medium.com/@angellopozo/uploading-an-image-to-ipfs-e1f65f039da4


Once youve uploaded a file, you get a link like this:
> https://gateway.ipfs.io/ipfs/QmNN5ogk6Lsc9vJh6gTF2tmPhGcxx1MC1H9XySct5LjJJY

and you can test your file using using webpagetest.org, e.g: https://www.webpagetest.org/result/180410_SP_e817a7c0a29a02651d0f71c13942e09a/
