## 📌 What is EC2?

Amazon EC2 (Elastic Compute Cloud) is a core AWS service that provides scalable virtual servers in the cloud.

It eliminates the need to purchase and manage physical hardware by allowing users to provision compute resources on demand. Instances can be launched within minutes, configured as required, and scaled based on workload.

---

### 🔹 Key Points

- Provides on-demand compute capacity
- Supports horizontal and vertical scaling
- Follows a pay-as-you-go pricing model
- Supports multiple operating systems (Linux, Windows)
- Integrates seamlessly with other AWS services

---

### 🏢 Real-Time Usage

- Hosting web applications and APIs  
- Running backend services (Java, Node.js, Python)  
- Managing CI/CD tools such as Jenkins  


---

## ⚙️ EC2 Instance Types

Instance types define the hardware configuration of an EC2 instance, including CPU, memory, storage, and networking capacity. Selection depends on workload requirements.

---

### 🔹 1. General Purpose

- Balanced compute, memory, and networking
- Examples: `t2`, `t3`, `t3a`

**Use cases:**
- Web servers  
- Small to medium applications  

---

### 🔹 2. Compute Optimized

- High CPU performance
- Examples: `c5`, `c6`

**Use cases:**
- Compute-intensive applications  
- High-performance APIs  
- Batch processing workloads  

---

### 🔹 3. Memory Optimized

- High memory capacity
- Examples: `r5`, `r6`

**Use cases:**
- Databases  
- In-memory caching systems (e.g., Redis)  
- Real-time data processing  

---

### 🔹 4. Storage Optimized

- High disk throughput and IOPS
- Examples: `i3`, `d2`

**Use cases:**
- Big data applications  
- Data warehousing  
- High-frequency read/write workloads  

---

### 🔹 5. GPU Instances

- GPU-based compute capability
- Examples: `p3`, `g4`

**Use cases:**
- Machine learning and AI workloads  
- Graphics rendering and video processing  

---

## 💰 EC2 Purchasing Options

AWS provides multiple pricing models to optimize cost based on workload characteristics.

---

### 🔹 1. On-Demand

- Pay per usage (hourly or per second)
- No long-term commitment

**Best suited for:**
- Development and testing  
- Short-term or unpredictable workloads  

---

### 🔹 2. Reserved Instances (RI)

- Commitment for 1 or 3 years
- Significant cost savings (up to ~70%)

**Best suited for:**
- Stable, long-running production workloads  

---

### 🔹 3. Spot Instances

- Deep discounts (up to ~90%)
- Can be interrupted by AWS at any time

**Best suited for:**
- Fault-tolerant applications  
- Batch processing and CI/CD workloads  

---

### 🔹 4. Savings Plans

- Flexible pricing model based on committed usage
- Applies across instance families and regions

---

### 🔹 5. Dedicated Hosts / Instances

- Physical servers dedicated to a single customer

**Best suited for:**
- Compliance requirements  
- Licensing constraints  

---
