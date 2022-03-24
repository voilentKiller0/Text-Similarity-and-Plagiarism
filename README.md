# Text Similarity and Plagiarism between two paragraph

Plagiarism detection based on noun arrays Implementation details are based on the paper
https://www.sciencedirect.com/science/article/pii/S1877050919315030 

1. Required Library
  
  ```
    nltk (Natural Language Toolkit)
    numpy
  ```
2. As input we take 4 paragraph
  - Plagiarism Paragraph
  - Original Paragraph
  - Reference Paragraph
  - Target Paragraph
  
   
  ```
  plag = "The legal system is made up of civil courts, criminal courts and specialty courts, such as family law courts and bankruptcy courts. Each court has its own jurisdiction, which refers to the cases that the court is allowed to hear. In some instances, a case can only be heard in one type of court. For example, a bankruptcy case must be heard in a bankruptcy court. In other instances, more than one court could potentially have jurisdiction. For example, a federal criminal court and a state criminal court would each have jurisdiction over a crime that is a federal drug offense but that is also a state offense."
original = "The legal system is made up of criminal and civil courts and specialty courts like bankruptcy and family law courts. Each court is vested with its own jurisdiction. Jurisdiction refers to the types of cases the court is permitted to rule on. Sometimes, only one type of court can hear a particular case. For instance, bankruptcy cases can be ruled on only in bankruptcy court. In other situations, it is possible for more than one court to have jurisdiction. For instance, both a state and federal criminal court could have authority over a criminal case that is also considered an offense under federal and state drug laws."
target ="Gardening in mixed beds is a great way to get the most productivity from a small space. Some investment is required, to purchase materials for the beds themselves, as well as soil and compost. The investment will likely pay-off in terms of increased productivity."
references ="If you don’t have a lot of space for a garden, raised beds can be a great option. Gardening in mixed beds is a great way to get the most productivity from a small area. Some investment is required. You’ll need to purchase materials for the raised beds themselves, as well as soil and compost. The investment will pay off, though, in the form of increased productivity."
  ```
 
3. As output we detect similarity between pargraph (Plagiarism and Original) and (Reference and Target)
  ![image](https://user-images.githubusercontent.com/55941465/159900993-a16b6d9a-4ac2-4b07-b91b-d1ec44880162.png)


# Thank you
