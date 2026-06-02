# scm-assistant-bot-
Supply Chain Risk Management Chatbot built using Flowise, Groq, Qdrant, and RAG architecture.
# Supply Chain Risk Management Chatbot

## Public Chatbot URL: https://cloud.flowiseai.com/canvas/9acbbc60-5619-4b36-b594-908d4fbbcc0a
https://cloud.flowiseai.com/canvas/cd6a2619-4fc6-45b4-bddc-8249b5e856af

Paste your chatbot URL here
https://cdn.jsdelivr.net/npm/flowise-embed/dist/web.js

## Technologies Used

* Flowise
* Groq (Llama 3.3 70B)
* Qdrant
* VoyageAI Embeddings

## Chunk Configurations Tested

### Configuration 1

* Chunk Size: 1000
* Chunk Overlap: 200

### Configuration 2

* Chunk Size: 500
* Chunk Overlap: 100

## Sample Questions and Answers





1.Tier-3 suppliers with an active disruption flag and response level:

The 11 Tier-3 suppliers with an active disruption flag are: Dravex Components India, Plataforma Metales SA, Maghreb Castworks, Helios Pack Greece, Cerromax Mineria, Orinoco Pack SAPI, Quetzal Textiles, Sibertek Molding, Archipelago PCB Corp, Varna Electronics EAD, Deltaforge Vietnam.
All of these suppliers are classified as High Risk and have an active flag, which requires a response level of Level 3 Activate per Policy §9. This involves CPO escalation and securing an alternate supplier for at least 40% of the volume.
Suppliers qualifying for the annual Volume Rebate Program:

2.There are 19 suppliers that qualify for the annual Volume Rebate Program.
These suppliers meet the criteria outlined in Policy §4.2, which includes being a Tier-1 supplier, having an On-Time Delivery (OTD) rate of 93% or higher, a defect rate less than 0.5%, and a Sustainability Score of 85 or higher.

3.Region with the highest total PO value and concentration limit breach:

The region with the highest total PO value is EMEA, with a total value of $193,987,179.91.
This represents approximately 48.5% of the total spend, which breaches the 45% regional concentration cap as per Policy §5.3. As a result, a Diversification Plan is required within 60 days.

4.Suppliers on the Supplier Watch List (SWL) status and restrictions:

There are 11 suppliers on the Supplier Watch List (SWL) due to having a Compliance Score less than 60.
These suppliers are: Deltaforge Vietnam, Maghreb Castworks, Helios Pack Greece, Cerromax Mineria, Orinoco Pack SAPI, Varna Electronics EAD, Quetzal Textiles, Plataforma Metales SA, Archipelago PCB Corp, Dravex Components India, Sibertek Molding.
Being on the SWL restricts new PO issuance to 20% of the prior quarter's volume as per Policy §3.4.

5.Product category with the highest average defect rate and Tier-2 limit:

The product category with the highest average defect rate is Mechanical Components, with an average defect rate of 2.12% across 360 POs.
This average defect rate is below the Tier-2 ceiling of 2.50% as specified in Policy §3.2, so it does not exceed the limit. However, it is approaching the limit

## Future Improvements

* Improve retrieval accuracy
* Enhance document chunking strategy
* Add conversation memory
* Support multiple document sources
* Improve supplier risk analytics
