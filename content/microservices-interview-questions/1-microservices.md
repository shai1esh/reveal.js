## Question
# What is Microservice?

--

# What is the interviewer looking for?
- Whether you know microservice architecture
- Few interviewers ask it as an ice breaker so that the interviewer can ask the next set of questions (since microservice is a huge topic)
- Bonus: if you can lay out some advantages and give some examples where applications can be built using microservices architecture

--

# Answer
- It is an architecture approach that structures a single application as a collection of small loosely coupled components or services 
- The services typically 
    - are independently deployable
    - are organized by business capability
    - communicate with one another using a mix of REST APIs, message brokers and event streaming
    - are small in size and implemented using different programming languages
    - have their own databases

---

## Question
# What are the advantages of microservice architecture?

--

# What is the interviewer looking for?
- Whether you have hands-on experience building microservice architecture
- Whether you know the difference between monolithic and microservice architecture and why microservice architecture is popular these days

--

# Answer
- It gives developers the freedom to independently develop and deploy services
- Precise scaling
- Better fault isolation (if one service fails, others will continue to work so only a part of application or particular functionality may go down)
- It is generally developed by a fairly small team
- It is easy to understand so new team members become productive easily and quickly

---

## Question
# Any disadvantages of microservice architecture?

--

# What is the interviewer looking for?
- Whether you have hands-on experience building monolithic architecture
- Whether you know the difference between monolithic and microservice architecture and when microservice isn't a good choice

--

# Answer
- Information barriers
- Latency and connectivity issues
- Testing all the services is complicated
- Deployment are more complicated and may need a well oiled DevOps team which has its own challenges
- Often result in duplication of effort

---