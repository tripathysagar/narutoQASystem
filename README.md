### narutoQASystem

As the advent of large transformer we can build a question answering system for a lage text data. In this repo, we will try to build up such system. For demonstration purpose we will be building a QA sys for Naruto(a frictional char). High label tasks
- We will be bs4 to crawl [Naruto Fandom Wiki](https://naruto.fandom.com/wiki/Narutopedia) and save it in the DB(mostly MongoDB)
- lets devide dataset in 80-10-10 train,valid,test
- as there is no list context-question-answer  to run transfer learing. TO resolve that, let's use SQuAD dataset to generate context-question pair 
- find answer for each pairs generated by the above step
- fine tune the process.
