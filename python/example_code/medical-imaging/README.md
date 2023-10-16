<!--Generated by WRITEME on 2023-10-13 17:49:16.323539 (UTC)-->
# HealthImaging code examples for the SDK for Python

## Overview

Shows how to use the AWS SDK for Python (Boto3) to work with AWS HealthImaging.

<!--custom.overview.start-->
<!--custom.overview.end-->

*HealthImaging is a HIPAA-eligible service that helps health care providers and their medical imaging ISV partners store, transform, and apply machine learning to medical images.*

## ⚠ Important

* Running this code might result in charges to your AWS account. For more details, see [AWS Pricing](https://aws.amazon.com/pricing/?aws-products-pricing.sort-by=item.additionalFields.productNameLowercase&aws-products-pricing.sort-order=asc&awsf.Free%20Tier%20Type=*all&awsf.tech-category=*all) and [Free Tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all).
* Running the tests might result in charges to your AWS account.
* We recommend that you grant your code least privilege. At most, grant only the minimum permissions required to perform the task. For more information, see [Grant least privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).
* This code is not tested in every AWS Region. For more information, see [AWS Regional Services](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services).

<!--custom.important.start-->
<!--custom.important.end-->

## Code examples

### Prerequisites

For prerequisites, see the [README](../../README.md#Prerequisites) in the `python` folder.

Install the packages required by these examples by running the following in a virtual environment:

```
python -m pip install -r requirements.txt
```

<!--custom.prerequisites.start-->
<!--custom.prerequisites.end-->

### Single actions

Code excerpts that show you how to call individual service functions.

* [Add a tag to a resource](medical_imaging_basics.py#L391) (`TagResource`)
* [Copy an image set](medical_imaging_basics.py#L337) (`CopyImageSet`)
* [Create a data store](medical_imaging_basics.py#L21) (`CreateDatastore`)
* [Delete a data store](medical_imaging_basics.py#L84) (`DeleteDatastore`)
* [Delete an image set](medical_imaging_basics.py#L369) (`DeleteImageSet`)
* [Get an image frame](medical_imaging_basics.py#L257) (`GetImageFrame`)
* [Get data store properties](medical_imaging_basics.py#L41) (`GetDatastore`)
* [Get image set properties](medical_imaging_basics.py#L202) (`GetImageSet`)
* [Get import job properties](medical_imaging_basics.py#L131) (`GetDICOMImportJob`)
* [Get metadata for an image set](medical_imaging_basics.py#L225) (`GetImageSetMetadata`)
* [Import bulk data into a data store](medical_imaging_basics.py#L101) (`StartDICOMImportJob`)
* [List data stores](medical_imaging_basics.py#L61) (`ListDatastores`)
* [List image set versions](medical_imaging_basics.py#L284) (`ListImageSetVersions`)
* [List import jobs for a data store](medical_imaging_basics.py#L152) (`ListDICOMImportJobs`)
* [List tags for a resource](medical_imaging_basics.py#L427) (`ListTagsForResource`)
* [Remove a tag from a resource](medical_imaging_basics.py#L409) (`UntagResource`)
* [Search image sets](medical_imaging_basics.py#L176) (`SearchImageSets`)
* [Update image set metadata](medical_imaging_basics.py#L310) (`UpdateImageSetMetadata`)

## Run the examples

### Instructions


<!--custom.instructions.start-->
<!--custom.instructions.end-->



### Tests

⚠ Running tests might result in charges to your AWS account.


To find instructions for running these tests, see the [README](../../README.md#Tests)
in the `python` folder.



<!--custom.tests.start-->
<!--custom.tests.end-->

## Additional resources

* [HealthImaging User Guide](https://docs.aws.amazon.com/healthimaging/latest/devguide/what-is.html)
* [HealthImaging API Reference](https://docs.aws.amazon.com/healthimaging/latest/APIReference/Welcome.html)
* [SDK for Python HealthImaging reference](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medical-imaging.html)

<!--custom.resources.start-->
<!--custom.resources.end-->

---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.

SPDX-License-Identifier: Apache-2.0