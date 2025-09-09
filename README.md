# q-dev-ide-pluginp-demo

## Basic Use Cases
- Code Explanation and Documentation
  - An Amazon Q Developer can explain code snippets or entire projects in natural language, making it easier for less technical users to understand what the code does.
  - It can help generate project documentation, user guides, or README files automatically so users can maintain up-to-date resources without manual effort.
- Project Planning and Design
  - Users can use Q to prepare for meetings by generating lists of requirements or initial design ideas based on project goals, or by asking about AWS services relevant to their project.
  - It assists in breaking down high-level problems into smaller, manageable tasks, making incremental progress easier for users who may not know best practices off-hand.
- Chat-Based Support and Troubleshooting
  - Amazon Q Developer provides chat interfaces in IDEs and DevSpaces, enabling users to ask questions about code errors, AWS resources, or workflow issues using natural language, without manually searching documentation.
  - It can suggest solutions and guide users step-by-step through troubleshooting and fix recommendations.
- Automated Routine Tasks
  - Q can auto-generate code snippets, refactor existing code, and even run deployment scripts for simple DevOps tasks, allowing users to automate routine actions directly from their workspace.
  - It helps non-experts navigate testing concepts, generate unit tests, or validate basic software operations, reducing the learning curve for new users.
- Features Supporting Less Technical Users
  - Natural language interface: Users interact conversationally rather than needing coding knowledge.
  - Integration with IDEs and DevSpaces: Available in popular editors, making access straightforward for beginners and less technical roles.
  - Step-by-step guidance: Promotes learning by breaking down tasks and offering explainable outputs that users can understand and reuse.


## Demo
- Pre-requisite
  - make sure Agentic Coding is enabled
- Prompt 1
  ```txt
  create a rust terminal application using the crossterm crate that displays the Commodore 64 color palettes (16 colors) as horizontal bars across the terminal
  screen. The bars should be arranged horizontally with a black rectangle in the center having a 16:9 aspect ratio and covering approximately 20% of the screen area.
  Define all 16 Commodore 64 colors with their RGB values, calculate terminal dimensions dynamically (making sure the math is right) and ensure the color bars wrap
  around the blackd rectangle with proper terminal cleanup when the application exits
  ```
- q chat process showcase (snapshots)
  <img width="1032" height="1116" alt="Screenshot 2025-09-09 at 20 34 10" src="https://github.com/user-attachments/assets/fc189b78-2fa8-43f6-bcb2-09c0e143cd0c" />
  <img width="1023" height="1137" alt="Screenshot 2025-09-09 at 20 34 27" src="https://github.com/user-attachments/assets/043bff15-e255-4466-9689-9611bd073882" />
- q generated file structure (snapshot)
  <img width="771" height="198" alt="Screenshot 2025-09-09 at 20 36 35" src="https://github.com/user-attachments/assets/940f16e2-2c55-40b1-97be-1d8e97612f55" />
- terminal running command
  ```sh
  cargon run
  ```
- app running showcase (snapshot)
  <img width="1439" height="685" alt="Screenshot 2025-09-09 at 20 38 45" src="https://github.com/user-attachments/assets/5684936c-b0d6-471f-be9f-49f15710fe15" />

- Prompt 2
  ```txt
  perfect! Now, enhance the rust terminal application by adding AWS S3 integration to count and display the number of buckets in an AWS account. Add the AWS SDK for
  Rust (aws-sdk-s3, aws-config) and tokio for async runtime support to the Cargo.toml file. Display "Number of Buckets:" text in bright green at the top left corner
  of the black rectange, connect to the AWS S3 using a specified profile (e.g., "personal") count the number of buckets and display this count as large ASCII art
  digits in magenta at the center of the rectangle. Implement proper error handling to show any AWS connection errors in red text, and ensure the ASCII art digits
  are properly centered within the rectangle.
  ```
- q chat process showcase (snapshots)
  <img width="1016" height="734" alt="Screenshot 2025-09-09 at 20 46 47" src="https://github.com/user-attachments/assets/6d6e3ec2-8b52-46df-a0c9-2aa4707afd27" />
  <img width="1018" height="1099" alt="Screenshot 2025-09-09 at 20 46 32" src="https://github.com/user-attachments/assets/466965a5-1a8a-4127-9499-3bdcc89e6410" />
- app running showcase (snapshot)
  <img width="1439" height="635" alt="Screenshot 2025-09-09 at 20 47 30" src="https://github.com/user-attachments/assets/a944030b-0d5b-4e20-bf7d-e105c546d077" />




 


  
