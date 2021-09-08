### Fundamental aspects of Google's core infrastructure
![image](https://user-images.githubusercontent.com/72551588/130631686-ad566f27-409e-44e3-a63a-0ba77df49b7c.png)
- Google Cloud: Top layer of products and services that you will interact with most often.
- Security: Base layer covers all of Google's apis.
- Compute Power, Storage, Networking: These allow you to process, store, and deliver business changing insights, data pipelines, and ML models
- Big Data and ML Products: Developed a top layer of big data and ML products to abstract away a lot of the hard work of managing and scaling that infrastructure for you.


![image](https://user-images.githubusercontent.com/72551588/130634732-aee21f37-be78-41ac-be78-12897a319348.png) 
- Moore's Law was a trend in computing hardware, but in the past few years growth has slowed dramatically as manufacturers run up against fundamental physics limits.
- Google solved this problem using ML designed new types of hardware specifically for.


![image](https://user-images.githubusercontent.com/72551588/130805796-939e3492-1aa3-40e6-b837-93cbe15305b2.png)
All classes have multi-region, dual-region, and region location options. They differ based on the access speed and the cost. So these belong to specific projects.


### Google Cloud Platform resource hierarchy
<p align="center"><img src="https://user-images.githubusercontent.com/72551588/130806985-42d832dd-e062-486d-8cd7-922787452004.png" style="margin:0"></p>
- To use Buckey, Buckey names have to be glovally unique.
- Project is a base-level organizing entity for creating and using resureces and services for managing billings, APIs, and permissions.
- Folders are another logical grouping you can have for collections of projects.
- The organization is a root node of entire GCP hierarchy.


### Google Cloud: Networking
Google's high-quality private network, petabit bisectional bandwidth, and Edge points-of-presence are combined using state- of-the-art software- defined networking to deliver a powerful solution. 
- Private network
  Google has laid thousands of miles of fiber optic cable that crosses oceans with repeaters to amplify optical signals
- Petabit bisectional bandwidth
  Google's Jupiter Network can deliver enough bandwidth to allow 100,000 machines to communicate amongst each other. So for any machine to communicate with any other machine in     the data center at over 10 gigabits per second.
- Edge network
  The network, Google's Network, interconnects with the public Internet at more than 90 internet exchanges and more than 100 points of presence worldwide. When an Internet user     sends traffic to a Google resource, Google responds to the user's request from an Edge network location that will provide the lowest delay or latency. Google's Edge caching       network places content close to end-users to minimize latency.
  
### Google Cloud: Security
![image](https://user-images.githubusercontent.com/72551588/130811325-fdc5a928-bbcb-4ba9-8d13-baccd5e3b394.png)
Google handles many of the lower layers of security like, the physical security of the hardware and its premises, the encryption of data on disk, and the integrity of the physical network. Because of its scale, Google can deliver a higher level of security at these layers, than most customers could afford to on their own. 
The upper layers of the security stack, including the securing of data, Google provides tools like Cloud IAM to help you implement the policies that you define at these layers.

![image](https://user-images.githubusercontent.com/72551588/131237517-cfb21de2-b9bd-4d55-ad28-c367916e4700.png)

![image](https://user-images.githubusercontent.com/72551588/131321613-e63828f2-ea19-4354-9128-561220bddd43.png)

![image](https://user-images.githubusercontent.com/72551588/131321691-fa4af37a-fce1-4228-be9b-57fb94e0b289.png)

![image](https://user-images.githubusercontent.com/72551588/131322577-506c3650-67f8-4774-8e63-d5f8ee10f30c.png)

![image](https://user-images.githubusercontent.com/72551588/131322669-673d15e2-c443-40d1-a7a5-426ed0a2de49.png)
