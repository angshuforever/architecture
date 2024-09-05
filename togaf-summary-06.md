## 7. TOGAF Reference Models

TOGAF provides two key reference models that serve as foundational architectures. These models can be used as a starting point for developing more specific architectures tailored to an organization's needs.

### 7.1 TOGAF Technical Reference Model (TRM)

The TOGAF Technical Reference Model (TRM) is a fundamental architecture upon which more specific architectures can be based. It provides a model and taxonomy of generic platform services.

**Key Components of the TRM:**

1. **Application Software:**
   - Represents the applications that support business functions and services
   - Includes both custom-developed and off-the-shelf applications

2. **Application Platform:**
   - Provides the services used by Application Software
   - Consists of various services categories:
     - Data Interchange Services
     - Data Management Services
     - Graphics and Imaging Services
     - Networking Services
     - Operating System Services
     - Software Engineering Services
     - Transaction Processing Services
     - User Interface Services
     - Security Services
     - System and Network Management Services
     - Location and Directory Services

3. **Communications Infrastructure:**
   - Provides the underlying network and communications capabilities
   - Supports distributed processing and interoperability between platforms

**Structure of the TRM:**

1. **Application Platform Interface (API):**
   - Defines the interface between applications and the underlying application platform

2. **Platform Entity:**
   - Represents the application platform itself, providing various services

3. **External Environment Interface:**
   - Defines how the application platform interacts with external environments and infrastructures

**Benefits of Using the TRM:**

1. **Standardization:**
   - Provides a common language for describing technical architectures
   - Facilitates communication between architects and stakeholders

2. **Consistency:**
   - Ensures a consistent approach to defining and describing technology services

3. **Reusability:**
   - Offers a foundation that can be reused across multiple architecture projects

4. **Gap Analysis:**
   - Helps identify gaps in current technology capabilities

5. **Vendor Independence:**
   - Provides a vendor-neutral view of technology services

**Applying the TRM:**

1. Understand the basic structure and components of the TRM
2. Customize the TRM to fit your organization's specific needs
3. Use the TRM as a checklist to ensure comprehensive coverage of technology services
4. Leverage the TRM to facilitate discussions about technology capabilities and requirements
5. Map your organization's specific technologies and products to the TRM components

### 7.2 Integrated Information Infrastructure Reference Model (III-RM)

The Integrated Information Infrastructure Reference Model (III-RM) is an extension of the TRM. It focuses on the application-level components and services needed to provide an integrated information infrastructure.

**Key Concepts of the III-RM:**

1. **Business Applications:**
   - Software applications that support specific business functions
   - Can be custom-developed or commercial off-the-shelf (COTS) products

2. **Infrastructure Applications:**
   - Provide common application services used by Business Applications
   - Examples include database management systems, directory services, and system management tools

3. **Application Platform Interface:**
   - Defines how Business and Infrastructure Applications interact with the underlying platform services

4. **Application Platform:**
   - Provides the core services and functions needed to run applications
   - Similar to the Application Platform in the TRM, but with a focus on information management and integration

**Key Components of the III-RM:**

1. **Business Applications:**
   - Brokering Applications
   - Data-Intensive Applications
   - Analytical Applications

2. **Infrastructure Applications:**
   - Data Management
   - Data Interchange
   - Data Warehousing
   - Workflow/Process Management
   - Metadata Management

3. **Application Platform Interface:**
   - Presentation and Distribution
   - Information Access and Exchange
   - Information Management

4. **Application Platform:**
   - Similar to the TRM, including services like Operating System Services, Network Services, etc.

**Benefits of Using the III-RM:**

1. **Integration Focus:**
   - Emphasizes the importance of information integration across the enterprise

2. **Information Management:**
   - Provides a comprehensive view of information management capabilities

3. **Service-Oriented Perspective:**
   - Aligns well with service-oriented architecture (SOA) principles

4. **Scalability:**
   - Supports the development of scalable and flexible information infrastructures

5. **Best Practices:**
   - Incorporates industry best practices for information management and integration

**Applying the III-RM:**

1. Understand the structure and components of the III-RM
2. Identify which components are relevant to your organization's needs
3. Use the III-RM to guide the development of your information infrastructure architecture
4. Leverage the III-RM to identify potential integration points and shared services
5. Map your organization's existing and planned information systems to the III-RM components

**Relationship between TRM and III-RM:**

- The III-RM builds upon and extends the TRM
- While the TRM focuses on general technology services, the III-RM emphasizes information management and integration
- Both models can be used together to provide a comprehensive view of the technical and information infrastructure

**Best Practices for Using TOGAF Reference Models:**

1. **Customization:**
   - Tailor the reference models to fit your organization's specific needs and context
   - Add or remove components as necessary, while maintaining the overall structure

2. **Mapping:**
   - Map your organization's existing and planned technologies and services to the reference model components
   - Use this mapping to identify gaps, redundancies, and integration opportunities

3. **Communication:**
   - Use the reference models as a communication tool with stakeholders
   - Leverage the models to explain complex technical concepts to non-technical audiences

4. **Consistency:**
   - Ensure consistent use of the reference models across architecture projects
   - Develop organizational standards for how the models should be applied and customized

5. **Evolution:**
   - Regularly review and update your customized reference models
   - Consider emerging technologies and how they fit into the model structure

6. **Integration with ADM:**
   - Use the reference models throughout the ADM cycle, particularly in the Technology Architecture phase
   - Leverage the models to ensure comprehensive coverage of technology and information infrastructure concerns

7. **Governance:**
   - Include the use of reference models in your architecture governance processes
   - Ensure that architecture projects align with the standardized views provided by the reference models

The TOGAF Technical Reference Model (TRM) and the Integrated Information Infrastructure Reference Model (III-RM) provide valuable frameworks for understanding and organizing technical and information infrastructures. By leveraging these models, organizations can develop more comprehensive, consistent, and well-integrated architectures that align with industry best practices and standards.

