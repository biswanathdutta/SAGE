# SAGE: Semantic Annotator for knowledge Graph Exploration 

SAGE is a desktop application for “thing” annotation. Here, “thing” refers to any concept (aka class), named individuals (aka entities), entity relations (aka object properties), and attributes (aka data properties). The system utilizes existing knowledge graphs (KGs) to convert any given input text into annotated things. The annotated "thing" can then either be browsed on the Web or retrieved along with its associated facts (axioms) from the knowledge base without writing a SPARQL query.  

SAGE's GUI makes it easy for users with less technological expertise to upload, annotate, and explore things from the KGs. The system displays the entity type hierarchy. It also shows the number of things available in the KGs and calculates their coverage against the input text.  

## SAGE primary features: 
1. Personalization- SAGE GUI provides an easy way to select and upload knowledge graphs on the system based on individual domain needs and annotation tasks. 
2. Exact Match- SAGE annotates the exact matched things within the text from the KGs. By clicking the annotated things, we can then browse them on the Web.  
3. Partial Match- SAGE provides an annotated list of partially matched things, in order to provide the user with contextually relevant resources (when no exact match is found). 
4. Predefined Query- Apart from annotating and exploring things on the Web as described above, SPARQL SELECT queries are defined on exact matches, which return all the tuples associated with the matched things. These queries are defined for each matched entity and the user does not have to write them. 
5. Identification of missing things in a KG- SAGE spots and lists the terms missing from the KGs along with their Parts-of-Speech (POS). 
6. Estimation of coverage of KG- The user can see the coverage of each KG against the uploaded domain literature in terms of the exact match found. 
7. KG statistics- SAGE displays the number of things in the KGs. This helps the user check the overall coverage of various KGs and compare them. 

## Usage Example: 
Example 1: Doctors and laboratory assistants can run their notes and transcription through SAGE to explore things (e.g., medical terms, diseases, drugs, viruses) that they are not familiar with. 

Example 2: SAGE can be utilized as a library tool to enhance the users reading experiences. For instance, it can be plugged into abstracting databases. This will enable readers to unearth things and their related facts while reading an abstract. 

(more use examples will be provided) 
