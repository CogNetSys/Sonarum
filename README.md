# About Sonarum

## Strategies

- E2EE - End-to-End Encryption of text, audio, and video channels. Encrypt data in motion and data at rest.
- Biometrics - Biometric confirmation prior to engagement deprecates the need to collect information.
- Minimization - Design the AI to ask for minimal and non-specific information. For instance, instead of asking for exact figures or details, the system could be designed to handle ranges or categories (e.g., income ranges rather than exact amounts), reducing the sensitivity of the data exchanged.
- Secure Data Tokens - Instead of transmitting sensitive data, use secure tokens that represent this data. The AI interacts with the tokens, which can only be decoded or used within a secure environment, ensuring that sensitive data is not exposed during processing.


## Tactics

- Collecting Personal or Sensitive Information Tactics:
    - SMS Link Strategy: The personal or sensitive information gathering step is diverted to a link sent by SMS to the users phone. Information is gathered from the user securely using text instead of audio or video.
    - Flow Control Strategy: When the step for collecting information arrives the question is posed by the AI but the answer is only received by Sonarum that masks the audio and shares the edited version with the AI. When the AI poses the question it also sends a text request to Sonarum to mask the response from the user.

## Sonarum Project Roadmap

### Phase 1: Requirements and Planning
- [ ] **Define Objectives**: Clearly outline what Sonarum aims to achieve.
- [ ] **Conduct Feasibility Study**: Evaluate the technical and financial feasibility of the project.
- [ ] **Engage Stakeholders**: Gather input from future users and stakeholders.

### Phase 2: Design and Architecture
- [ ] **Design System Architecture**: Draft a comprehensive design of how components interact.
- [ ] **Select Technologies**: Finalize the technologies for each component of the system.
- [ ] **Create Data Flow Diagrams**: Develop diagrams that detail the flow of data through the system.

### Phase 3: Development
- [ ] **Setup Development Environment**: Establish environments and version control systems.
- [ ] **Develop Components**: Build individual components such as custom GStreamer plugins.
- [ ] **Develop APIs**: Document and create APIs for internal and external communication.

### Phase 4: Integration and Testing
- [ ] **Integrate Components**: Systematically integrate and configure all components.
- [ ] **Execute Testing**: Perform unit, integration, performance, and security testing.

### Phase 5: Deployment
- [ ] **Plan Deployment**: Outline the steps and strategies for deployment.
- [ ] **Pilot Deployment**: Start with a limited deployment to test under real conditions.
- [ ] **Full Deployment**: Extend the deployment across all target environments.

### Phase 6: Maintenance and Scaling
- [ ] **Implement Monitoring**: Set up tools to monitor the system’s performance.
- [ ] **Establish Feedback Mechanisms**: Create channels for collecting user feedback.
- [ ] **Plan for Scalability**: Prepare strategies to scale the system as needed.

### Phase 7: Documentation and Training
- [ ] **Produce Documentation**: Write detailed documentation covering all aspects of the system.
- [ ] **Organize Training Sessions**: Develop and conduct training for end-users and administrators.

### Continuous Improvement
- [ ] **Schedule Regular Updates**: Plan for regular system reviews and updates based on feedback and new technologies.
