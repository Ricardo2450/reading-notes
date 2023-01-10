# Serverless Functions

> ## [What is Serverless Computing?](https://www.ibm.com/cloud/learn/serverless)

* Serverless is a cloud computing application development and execution model that enables developers to build and run application code without provisioning or managing servers or backend infrastructure.

* With serverless, developers never pay for idle capacity.

* The billing starts when execution starts, and ends when execution stops; typically, pricing is based on execution time and resources required

* Faas - Function-as-a-service. A cloud computing service that enables developers to run code or containers in response to specific events or requests, without specifying or managing the infrastructure required to run to code.

* FaaS services include:
  * Serverless databases and storage
  * Event streaming and messaging
  * API gateways

* Provisioning time: Measured in milliseconds for serverless, vs. minutes to hours for the other models.

* Administrative burden: None for serverless, compared to a continuum from light to medium to heavy for PaaS, containers and VMs respectively.

* Maintenance: Serverless architectures are managed 100% by the provider. The same is true for PaaS, but containers and VMs require significant maintenance including updating/managing operating systems, container images, connections, etc.

* Scaling: Auto-scaling—including auto-scaling to zero—is instant and inherent for serverless. The other models offer automatic but slow scaling that requires careful tuning of auto-scaling rules, and no scaling to zero.

* Capacity planning: None needed for serverless. The other models require a mix of some automatic scalability and some capacity planning.

* Statelessness: Inherent for serverless, which means scalability is never a problem; state is maintained in an external service or resource. PaaS, containers and VMs can leverage HTTP, keep an open socket or connection for long periods of time, and store state in memory between calls.

* High availability (HA) and disaster recovery (DR): Both are inherent in serverless with no extra effort and at no additional cost. The other models require additional cost and management effort. In the case of both VMs and containers, infrastructure can be restarted automatically.

* Resource utilization: Serverless is 100% efficient because there are no such things thing as idle capacity—it is invoked only upon request. All other models feature at least some degree of idle capacity.

* Billing granularity and savings: Serverless is metered in units of 100 milliseconds. PaaS, containers and VMs are typically metered by the hour or the minute.

* Kubernetes - An open-source container orchestration platform that automates the deployment, management and scaling of containers
  * Note: Kubernetes can't run serverless apps without specialized software that integrates Kubernetes with a specific cloud provider's serverless platform.

* Pros of serverless:
  * Improved developer productivity
  * Pay for execution only
  * Develop in any language
  * Streamlined development/DevOps cycles
  * Cost-effective performance
  * Usage visibility

> ## [venv - Creation of Virtual Environments](https://docs.python.org/3/library/venv.html)

* venv module supports creating lightweight “virtual environments”, each with their own independent set of Python packages installed in their site directories

* Multiple paths can be given to venv, in which case an identical virtual environment will be created, according to the given options, at each provided path.

* How to activate your virtual environment: $ source \<venv>/bin/activate

> ## [Vercel - Get Started](https://vercel.com/docs/get-started)

* Whenever you create a new Project on Vercel, the platform will try to preselect the right default configuration for you.

* On Vercel, this Domain can have any format of your choosing:
  * acme.com (apex domain)
  * blog.acme.com (subdomain)
  * *.acme.com (wildcard domain)

* If you already own a Domain, you will be able to point it to Vercel, or transfer it over.

* Whenever new commits are pushed to the Git repositories associated with your Vercel Projects, the last commit of every push will automatically trigger a new Deployment within that respective Project.

> ## [What is Serverless?](https://www.youtube.com/watch?v=vxJobGtqKVM)

* Draw backs of serverless
  * timeouts
  * latency issues
  
* Benefits of serverless:
  * You pay for execution only
  * auto scalables
  * faster time to market
  * polyglot environment
  * highly available

> ## Other reads

* [http.server](https://pymotw.com/3/http.server/index.html)

* [Requests){:target=”_blank”}](https://requests.readthedocs.io/en/latest/)

* [Python & APIs](https://realpython.com/python-api/)

* [Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions)

* [Effective Python Environment](https://realpython.com/effective-python-environment/)

[Return Home](../README.md)
