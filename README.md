# AI-supported Market Analysis of Compensation & Benefits in M&A Integrations

## Case Introduction

Mergers and acquisitions (M&A) create significant challenges for companies, particularly in aligning compensation and benefits systems between the merged organizations. PricewaterhouseCoopers GmbH WPG (PwC), one of Germany’s leading auditing and consulting firms, frequently addresses this issue during post-merger integration, where different compensation structures must be harmonized. An objective and up-to-date overview of market compensation and benefits is essential to ensure fairness, maintain employee satisfaction, and support a smooth transition.

Job advertisements are a rich but unstructured source of data reflecting current market compensation and benefit trends across industries, regions, and company sizes. Extracting meaningful insights from this data requires automated, AI-supported methods capable of processing large volumes of textual information efficiently.

In collaboration with PwC, our project developed an **AI-based market analysis tool** that uses web scraping and natural language processing (NLP) to continuously collect, extract, and visualize compensation and benefits data from job advertisements. This tool provides PwC consultants with **evidence-based insights** to guide decision-making during post-merger integration.

## Motivation

The financial and strategic stakes of compensation misalignment during post-merger integration are substantial, with failed integrations often resulting in 20-40% talent exodus within the first year, directly undermining projected synergies and costing merged entities millions in unrealized value.

Traditional compensation surveys lag behind rapidly shifting market dynamics by 6-12 months, leaving companies vulnerable to outdated decision-making precisely when speed and accuracy are most critical. In Germany's highly regulated employment environment, compensation decisions must also comply with complex labor laws and works council requirements, where misaligned structures can trigger legal challenges and regulatory scrutiny.

Beyond compliance, compensation equity is fundamental to cultural integration success—perceived unfairness creates lasting divisions between legacy employee groups, undermining the cohesion necessary for merger success. Manual compensation analysis is not only time-intensive and prone to bias, but also fails to scale effectively as PwC handles multiple merger integrations simultaneously.

An AI-driven tool that continuously monitors real-time market standards addresses these interconnected challenges by providing scalable, objective, and evidence-based insights that protect human capital investments, ensure regulatory compliance, build employee trust, and enable consistent service delivery across diverse client portfolios.

## Project Tasks per group member

The project was structured into three main tasks, distributed among the team:

1. **Data Source Identification and Web Scraping**  (Philipp)
   Identify accessible job advertisement sources and develop a reliable web scraping tool to enable continuous data extraction. Here is the repository with the web scrapers and a complete documentation:

2. **Natural Language Processing (NLP) Pipeline**  (Tom)
   Design and implement an NLP pipeline to extract structured information from unstructured job advertisement texts, including qualifications, compensations, and benefits.
   This part consits of three elements: the Mongo-Database extraction, the data strucutring using NLP and the storage of the information in SQlite.<br>
   Here is a link for more details about the different parts: https://github.com/tomz2000-lab/PJS_Pipeline

3. **Comprehensive Survey of Compensation and Benefits Trends and Dashboard Development**  (Larissa)
   Conduct a literature review and empirical analysis of compensation and benefits trends to compare academic recommendations with market reality. Additionally, develop a dashboard to visualize and present the analyzed data effectively.
