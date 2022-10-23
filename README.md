# CS470 - Migrating a Web-Application to the Cloud

[![Tyler Coplan's Cloud Migration Presentation](https://img.youtube.com/vi/OabwCjmzSMo/0.jpg)](https://www.youtube.com/watch?v=OabwCjmzSMo)

## Course Reflection
### Experiences and Strengths: Explain how this course will help you in reaching your professional goals.
<strong>What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?</strong>

This course has given me the skills to create a web application from local prototype to a working application deployed on the cloud. From securing the web application to creating APIs and database communications, I have learned how to create and deploy a full-stack web application on the cloud.

<strong>Describe your strengths as a software developer.</strong>

My biggest strength is that I love to solve problems. It bothers me when something does not work the way it should work and I get a bit obsessive over getting it right. I know that in a professional environment that this will require prioritization and balancing with the overall business needs, but the drive to solve problems helps me get the work done. I may not know the answer, but I am resourceful and I can break problems down to their root cause and figure out what needs to be done to solve them.

<strong>Identify the types of roles you are prepared to assume in a new job.</strong>

I am prepared to assume the role of an entry level developer. I do not have enough experience working in a professional system to understand how to develop them at this point. However, I can take the requirements and code a solution to meet the needs. I can test and debug as well. I am comfortable using Windows and Linux development tools and now I even have some experience with cloud development tools.

### Planning for Growth: Synthesize the knowledge you have gathered about cloud services.
### Identify various ways that microservices or serverless may be used to produce efficiencies of management and scale in your web application in the future. Consider the following:

<strong>How would you handle scale and error handling?</strong>
For handling scale, I would look at optimizing the solutions as needed. A function that gets called a thousand times per hour has much different needs than a function thats called a few dozen times a day. On these scales, optimizing memory and compute time will give a significant reduction in operating costs. For error handling, always handle errors cleanly. Produce an error page to the customer that clearly explains that the information they thought they were getting is unavailable, or that the data they thought they were entering did not get entered. Provide them with a link back to the site or even trigger it automatically for them. Log the error with as much information as possible, such as date, time, file and function the error occurred in, if possible.  Send a notification about the error to the development team so it can be researched and addressed.

<strong>How would you predict the cost?</strong>

I would measure performance of computing functions, gather data about the database storage requirements and file storage needs, and calculate costs based on expected usage. 

<strong>What is more cost predictable, containers or serverless?</strong>

I do not know the answer to this, although I think containers would be more predictable. I am assuming this question means containers run on the business' own servers. That would likely be a relatively fixed cost to the business. Serverless computing is a pay-for-use platform, so more usage costs more money. However, the resources scale automatically and you do not have to pay if you are not using resources. This is why it seems to me that containers would be a more predictable cost. But, presumably, more usage leads to more cost, but also more business, so the less predictable cost may not be a bad thing.

<strong>Explain several pros and cons that would be deciding factors in plans for expansion.</strong>
From a technical perspective, the more cloud services you use, the less you have to pay per resource. So needing more computing resources from the cloud would be more cost effective on a per resource basis. Expaning would also lead to higher usage, which can allow the business to collect more data on their customers to better inform business decisions. Some cons to consider would be scaling applications. The more they get used, the more crucial it is to ensure they are as efficient as feasible to eliminate waste. Also, database transactions become more complex to guarentee ACID transactions as more users attempt to read and write from them simultaneously.

<strong>What roles do elasticity and pay-for-service play in decision making for planned future growth?</strong>

Elasticity allows a cloud application to scale automatically with customer needs. Pay for service means the more you use, the more you pay. So, you have to consider realized business gains compared to increased usage of the web application. At some point, it could make more sense to house your own servers depending on the business model and needs. Each comes with their own risks and benefits that need to be considered to make the best choice, and there is no one-size-fits-all solution.
