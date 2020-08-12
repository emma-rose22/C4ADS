# Center For Advanced Defense Studies

I worked on this project with a team of Data Scientists for C4ADS. For two months we worked as their interns to solve the difficult problem of tagged trade transactions as 
being involved in nuclear trade. We were given 65 million rows of data in a non-English language, with the hope we could apply ML techniques to this labeled/unlabeled dataset. 
Due to the sensitive nature of the data, we are not permitted to share the data directly, or display the true results of our pipeline. However, the paper written by my fellow team
member, Tyler Russin, who I designed the architecture of the project with, does a very in-depth breakdown of our process. After thoroughly exploring various ML techniques, as well
as clustering to confirm a lack of relationship, we ended up building a massive dictionary to translate the entire dataset into English, before creating a list of all
words or products that suggested involvement in the nuclear production process. Using this, we were able to tag each individual transaction and return a dataset of tagged transactions.


This was executed in AWS, pulling data from S3 buckets using an EC2 script that executes the functions described above. This lead me to becoming familiar with AWS services,
before picking the one most appropriate for our solution. This project was exciting and dynamic, asking us to shift our expectations and solution as we delved deeper into the 
data and discovered the patterns held within. I am very satisfied with our final product, as was our stakeholder at C4ADS, as we were able to deliver a better solution than
any group before us. Please give this research paper a read to fully understand our process. 
