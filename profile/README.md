## Hi there!
This is the welcome page of the airqi.com github organization!

We are developing an open-source air pollution platform with maximum transparency.

Here are some ideas to get you started:

## 👋 Before You Start

Read our Manifesto in here: 
and then you can join in.

## 🌈 Contribution guidelines:

We have two main repositories of the platform: the frontend https://github.com/ and the backend https://github.com/

Start by setting up your frontend and backend locally reading the instructions in the `frontend/README.md`
Check the issues and select one you'd like to work on - write in it so that it can be assigned to you
We work with forks, submit PRs, review, aprove and only maintainers can merge and deploy - more about forks: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks
The automated tests will help you add improvements safely, please extend them too

## 👩‍💻 Communication:

Our Discord community server here: https://discord.com
When you join follow the instructions to present yourself and contact a community lead in the area of your contribution.

## 🌵 System Design
The system design section of our README file contains detailed information about the overall structure of our platform. This includes diagrams and explanations of the different components and how they interact.
![image](https://github.com/airqi-com/.github/assets/15163891/447c570a-631c-433d-8437-936d687f6808)
In a Kubernetes environment, the Load Balancer (Cache) acts as the entry point for all incoming requests. It distributes the requests to various instances of the services based on the load, ensuring that no single instance becomes a bottleneck. It may also cache responses to reduce the load on the backend services.
