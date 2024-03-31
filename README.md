# CLoudandserverless
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/aa1b8aae-204b-4120-bdaa-5c3559567308)
Creation of Amazon S3 bucket:
i)	Allocate a unique name to your bucket 
ii)	Make sure you enable versioning
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/78ce16e2-8682-4e6f-9b2b-7bac131312c3)
Upload a image into the bucket
Image name: website.jpg
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/cc3513d3-5a84-4f1f-bd86-a6a6fe7a5e3a)
In cloud formation create a stack with the name image-resize
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/941d7387-3f45-4a40-a157-4e367eae659c)
In the demo url click the link shown , after which you will be directed to a Handler.
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/1b7b388a-f24c-4935-86fd-09965843c4f4)
In the handler you need to enter the name of the S3 bucket and the name of the image.
After which you need to click on import and your image will be imported.
After importing in the editor you can change the different properties of image like width, height, background color, RGB etc…..
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/3c9728f1-b709-4b79-afa0-937c353e9e62)
After doing all the changes on the editor you need to click on preview and the changes will be applied to the image.

Another way is by clicking the link of api endpoint and you need to add the key of the image to that link ‘/key’
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/d43e7c93-2e8f-4645-b665-b36591f5229e)
After your image is displayed you can do changes by applying changes to the URl.
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/0e5fcdc7-8d49-497d-9bc5-6a8b83a982cf)
These are the different types of changes that can be made.
For example if I apply the resize option you will get the final output.

OUTPUT
![image](https://github.com/Jeevan817/CLoudandserverless/assets/110009201/ee73e055-5cb0-4596-8a35-811a53b84f6b)
