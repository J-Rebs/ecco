# Ecco 💬

> *"Ecco!"* — Italian for *"Here it is!"* or *"Behold!"*

Another AI Chatbot. 

# What is this repo?

This repo is meant to serve as a learning environment for building an open source chatbot. 

# What is the development philosophy behind this repo? 

1. Learning and development are iterative. Relatedly, good things develop slowly then suddenly. 
2. AI should aid development but not supplant learning. For example, using AI to scaffold a repo or do something you understand already is fine. Asking AI to replace the full coding process or write more code than you can comprehend is not.
3. Rabbit holes are part of the proccess. 
4. There is still an overall objective - build an efficient chatbot that aids but doesn't replace independent thinking and avoids delusional statements.


# A general roadmap

First, this project will seek to build a very useful "local chatbot". This chatbot will run as a local program and not reqiure web resources. It may or may not have some form of persisted data, but this will not be very durable. For example, maybe the data is just kept on some desktop file. If this file is deleted, data is lost.

As part of the first goal, the chatbot should also have guardrails and ethics included. It shouldn't be able to do things which are nefarious as we the developers define it. Whether that is possible should be engaged with directly. In some ways, we are just going to wrap open weight models, but we should still be thoughtful.

If the first goal succeeds, the second goal will seek to develop a portable deployment system for the chatbot. That is to say the chatbot can be deployed on a variety of cloud providers without locking into a given providers way of doing things. For example, this online chatbot might use an open source no-sql database vs say dynamodb. This does not have to be a super scalable system.