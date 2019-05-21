**Beginner level efforts in e-Learning for GTPB content**

This repository accumulates the results of a series of experiments performed at the ELIXI-PT node, while working in the e-learning subtask of the WP11: ELIXIR Training Programme of the EXCELERATE project (2015-2019). ELIXIR-EXCELERATE is funded by the European Commission within the Research Infrastructures programme of Horizon 2020, grant agreement number 676559.

These experiments consist of trying to build interoperable e-learning materials using the ADDIE Model for Instructional Design
as sggested at the GOBLET/ELIXIR-EXCELERATE Workshop on e-learning hosted by the Instituto Gulbenkian de Ciência (IGC) in November 2017. The talk presented by Sara Petiz [GOBLET/ELIXIR-EXCELERATE Workshop on e-learning](https://github.com/alexcaetano/GTPB_Elearning/blob/master/GOBLET_ELIXIR_Workshop_elearning_SaraPetiz_21112017.pdf) brought us in contact with design issues and ways of developing materials, allowing us to play with some of the tools.

Our aim is to gain experience in producing content using SCORMs, while evaluating the particular implications of incorporating existing training material, namely the rather large collection of content that results from documenting Face-to-Face (F2F) training courses.



**Building Learning Objects and Shareable Content Object Reference Model (SCORM)**

- **Why is it important to develop SCORM compliant content?**

      • To be able to reuse content
    
      • To be able to share content with heterogeneous LMS
    
      • To be able to share performance results collected from participants
    

For a more comprehensive reference about what a SCORM is and how it works you can explore several online resources: 
[SCORM explained](https://scorm.com/scorm-explained/) 
[the Cookbook](https://scorm.com/scorm-explained/scorm-resources/scorm-cookbook/) 
[and specific to v1.2](https://scorm.com/wp-content/assets/cookbook/CookingUpASCORM_v1_2.pdf).

For a more comprehensive reference about the benefits of using a SCORM you can [explore](https://scorm.com/scorm-explained/business-of-scorm/benefits-of-scorm/)



- **The SCORMs produced**

 For experimental purposes we aimed to explore as many different strategies as possible, namely:
 
      [x] Develop e-learning content from scratch
      
      [x] Develop e-learning content based on the documentation from F2F courses
      
      [x] Develop e-learning content from an online course website in html
      
  And experimented with some different resources to accomplish our goal. For instance:
  
      [x] Producing SCORMs using the Adapt Authoring Tool
      
      [x] Producing SCORMs using other software tools
      
      [x] Importing SCORMs into an Learning Management System (LMS), in particular Moodle Cloud
      

So far we produced e-learning content for four themes from courses hosted by the GTPB programme. Below you can find a detailed description of what you will find in each output (i.e. SCORM).

   - **Loops**
   
   
        - Origin - Online [Python 3 - An Introductory Tutorial](https://rawgit.com/BioinformaticsTraining/Critical-Guides/gh-pages/HTML/Python_Bits.html#Section-XI) course, Section XI (yet in construction by David Philip Judge)
            
   
        - [Learning object content](https://github.com/alexcaetano/GTPB_Elearning/blob/master/SCORMs/loops_module.zip) - It contains a standalone module with:
       
                    - Prerequisites section
        
                    - Syntax section
        
                    - Practical examples to try out
        
                    - Self-assessment section
        
                    - Sum-up of topics introduced
        
        
        
        - Component elements:
      
                    - .mp4 video format
            
                    - text 
                   
                    - accordion elements (collapsible content) 
            
                     - multiple choice questions

    
       - Tool used - [Adapt Authoring Tool](https://www.adaptlearning.org/)
       
        
   - **Proteomics Data Analysis**
     
     
        - Origin - [PDA19](https://gtpb.github.io/PDA19/) Github webpage 
            
       
        - [Learning object content](https://github.com/alexcaetano/GTPB_Elearning/blob/master/SCORMs/proteomics_overview.zip) - It contains the overview of the course:
     
                   - Course instructors section
                   
                   - Course description section
                   
                   - Target audience section
                   
                   - Prerequisites section
                   
                   
        
        - Component elements:
             
      
                   - hot graphic (use of images as pins)
            
                   - text 
                   
                   - hyperlinks to youtube videos

    
        - Tool used - [Adapt Authoring Tool](https://www.adaptlearning.org/) 
      
      
      
      
   - **Computational Pangenomics**
     
     
        - Origin - [CPANG18](https://github.com/GTPB/CPANG18/blob/master/index.md) Github webpage 
             
       
        - [Learning object content](https://github.com/alexcaetano/GTPB_Elearning/blob/master/SCORMs/pangenomics_overview.zip) - It contains the overview of the course:
     
                   - Course instructors section
                   
                   - Course description section
                   
                   - Target audience section
                   
                   - Course methodology section
                   
                   - Learning objectives section
                   
        
        - Component elements:
             
      
                   - hot graphic (use of images as pins)
            
                   - text 
                   
                   - accordion elements (collapsible content)
                   
                   - images

    
       - Tool used - [Adapt Authoring Tool](https://www.adaptlearning.org/) 



   - **Research Data Management**

This course is being created by Rutger Vos in collaboration with the GTPB team. 

The experiment is an attempt to use a conversion tool that uses the lib2scorm  [Markdown to SCORM](https://github.com/naturalis/markdown2scorm). Nowadays, the majority of the GTPB course materials is developed using Markdown using GitHub. With this method we expect to be able convert existing material with some automation.

The Adapt Authoring tool was chosen to create the self-assessment quizzes. You can download the resulting  [SCORM](https://github.com/alexcaetano/GTPB_Elearning/blob/master/SCORMs/data_management_assessment.zip) and upload it to the LMS of your preference.





