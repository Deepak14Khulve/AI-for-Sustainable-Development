Welcome to the AI Sustainable Development Project:
Automated Text Classification Using the OSDG Framework

(https://miro.medium.com/v2/resize:fit:640/format:webp/0*eXgmA-iKFS_SxGCz)

**OSDG** is an open-source tool that maps and connects activities to the UN Sustainable Development Goals (SDGs) by identifying SDG-relevant content in any text.
The OSDG tool is available free of charge at [OSDG.ai](https://www.osdg.ai/).

The tool supports the following types of input:

1. **Text fragments**
2. **PDF files**.


The system uses state-of-the-art neural **machine translation** models to translate the input into English. OSDG currently supports **15 languages**: English, Arabic, Danish, Dutch, Finnish, French, German, Italian, Korean, Polish, Portuguese, Russian, Spanish, Swedish, and Turkish.

For each query, we return a detailed breakdown of all SDGs found in the text, entitled the **OSDG Wheel**. You can learn more about it [here](https://osdg.ai/news/OSDG-launches-the-OSDG-Wheel-with-detailed-SDG-data-breakdowns).

## Methodology

OSDG 2.0 works in two stages. The first stage uses machine learning (ML) models, trained on the data collected via the OSDG Community Platform (CP). You can access this data through the [osdg-data](https://github.com/Deepak14Khulve/AI-for-Sustainable-Development.git) repository. These models carry out the initial screening of texts and suggest the preliminary SDG labels. In the second stage, OSDG uses its ontology/keyword map to verify the initial labels. To assign a specific SDG label, **both the ML and ontology approaches must be in agreement**.

