# IIIFStack
### AWS CloudFormation Stack Template for building a serverless implementation of the International Image Interoperability Framework
### The API specification is from the [version 2.1 IIIF image API available here](https://iiif.io/api/image/2.1/)

At present, this demonstration stack for CloudFormation only implements a bare minimum selection of the IIIF Image API functions, has no error handling, and no authentication.  It therefore cannot be used as a working target for an IIIF client software at this time, and is exclusively a work in progress.

In order to use this template to create a stack, you will need to have already created Python Lambda layers for imagecv2 and boto3, and have their associated ARNs to feed into the stack's parameters.  [A tutorial video on how to create Lambda layers is available here.](https://www.youtube.com/watch?v=FQBT8vVRkAg)
