# ERROR: NO HOSTED PARALLELISM HAS BEEN PURCHASED OR GRANTED

Greetings my fellow Technology Advocates and Specialists.

In this Troubleshooting Session, I will demonstrate, how I resolved the encountered error - "__No Hosted Parallelism has been Purchased or Granted__" while executing Azure DevOps Pipeline.

Very Recently, I created __one additional New DevOps Organisation.__

Below follows the Details:-

| __KEY__ | __VALUE__ |
| --------- | --------- |
| __DevOps Organisation URL__ | https://dev.azure.com/AM0704 |
| __DevOps Organisation Owner__ | __AM@mitra008.onmicrosoft.com__ |
| __DevOps Project__ | __AMCLOUD__ |
| __DevOps Service Connection__ | __amcloud-cicd-service-connection__ |
| __Repo Name__ | __AMREPO__ |

As soon as I executed my First Pipeline on __Microsoft Hosted Build Agent__, below error was encountered:-

| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fszy0dd5yu79bv1q1d2p.jpg) |
| --------- |

When verified under __DevOps Organisation Settings > Pipelines > Parallel jobs > Private projects__, Parallel Jobs was set to 0 for Microsoft-Hosted. 

Reference Screenshot follows below:-

| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4xmr6ax7glczucx7fvn4.jpg) |
| --------- |

Browse to below link (__It was mentioned in the error screenshot.__)

| https://aka.ms/azpipelines-parallelism-request |
| --------- |

Fill the Form and Submit. Microsoft then takes 2 -3 Business Days to process the Request.

| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/o96crst7paa1ndunerq5.jpg) |
| --------- |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/km89mh2c7ef47t68eo1r.jpg) |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/60szjr5yyhcv34bkhktm.jpg) |

__Free Tier Request__ was then completed by Microsoft. 
Below is how the Email Response from Microsoft looks like:-

| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vpyatx1qkkag8hf2bem8.jpg) |
| --------- | 

Changes are reflected in DevOps Organisation.

| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4xxsk8ztl0lyodnzwtcd.jpg) |
| --------- |

Finally, when Pipeline is executed again, __Earlier Encountered Error was no more found. It was Resolved.__

| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ggxvqeoq009jg86oocsn.jpg) |
| --------- |

 
__Hope You Enjoyed the Session!!!__

__Stay Safe | Keep Learning | Spread Knowledge__
