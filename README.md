# National ID Document Data Extraction Service

## Service Route
`/idrecognizer/idrecognizer`

## Description
The service allows an image of a national identity card attached to a workflow to be sent to an MS Azure endpoint via a webhook. The Azure service analyzes the image, extracts relevant data, and writes it back into the corresponding Workspace workflow variables.

## Dedicated Template Variables
- **idCountryRegion**: The country or region of the ID document.
- **idRegion**: The region specified on the ID document.
- **idDocumentNumber**: The document number of the ID.
- **idDocumentDiscriminator**: A discriminator value on the document.
- **idFirstName**: The first name of the ID holder.
- **idLastName**: The last name of the ID holder.
- **idAddress**: The address of the ID holder.
- **idDateOfBirth**: The date of birth of the ID holder.
- **idDateOfExpiration**: The expiration date of the ID document.
- **idDateOfIssue**: The date when the ID document was issued.
- **idEyeColor**: The eye color of the ID holder.
- **idHairColor**: The hair color of the ID holder.
- **idHeight**: The height of the ID holder.
- **idWeight**: The weight of the ID holder.
- **idSex**: The sex of the ID holder.
- **idPersonalNumber**: The personal number on the ID document.
- **idPlaceOfBirth**: The place of birth of the ID holder.

## Supported File Formats
- **pdf**
- **jpeg**
- **jpg**
- **png**
- **bmp**
- **tiff**
- **heif**

## Further Information
For more information about the MS Azure service, please visit the [Azure ID Document Extraction Documentation](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/concept-id-document?view=doc-intel-4.0.0#iddocumentnationalidentitycard).

---

This service is part of the Itiner Workspace integrations and is designed to facilitate the extraction and processing of national identity card data by leveraging MS Azure's document intelligence capabilities.
