## Africa
Johannesburg, South Africa - Cloud (General MainNet Node)
 - Status: Active
 - CPU: 3 cores
 - RAM: 6GB
 - HDD: 100GB
 - Network: 1Gbps

Johannesburg, South Africa - Physical (General MainNet Node)
 - Status: Active
 - CPU: 8 cores
 - RAM: 32GB RAM
 - HDD 15k SAS: 600GB
 - Network: 1Gbps

## United States of America
US East Coast - Amazon M5.2xlarge (SR Witness Node)
 - CPU: 8 cores
 - RAM: 32GB RAM
 - SSD: 100GB, with 400 guaranteed IOPS
 - Network: 10Gbps, with Elastic IP

Post SR27 inclusion, US East Coast - Amazon c5.18xlarge (SR Witness Node)
 - CPU: 72 cores
 - RAM: 144GB RAM
 - SSD: 1TB, with 600 guaranteed IOPS
 - Network: 25Gbps, with Elastic IP

 - We would also aim to run on direct hardware and Microsoft Azure cloud, as there seems to be a large dependency on the Amazon network by SR's, due to the price/performance ratio. Would a significant Amazon outage distrupt the Tron network in its current state?
 
 - All production servers to run secure linux distribution, with active monitoring service
 - Operational maintenance and patching to be automated, and verified not less than once per week
 - Servers are a mix of bare-metal and cloud based
