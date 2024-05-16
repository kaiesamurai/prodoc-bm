
# ProDoc

ProDoc is a private document editor where you can write and share documents anonymously. It's perfect for storing sensitive data like passwords and confidential information. Once you save a document on our database, you can access it anywhere using your wallet. Our security protocol ensures that your documents remain encrypted on our database, protecting your privacy. We leverage wallet signatures for authentication and a combination of AES encryption and MetaMask's decryption features. Our application uses noir for writing and generating Zero-Knowledge Proofs (ZKPs), and everything runs locally in the browser. 


## Inspiration

Our inspiration for ProDoc stemmed from the need for a secure and anonymous document editor, where users could confidently store sensitive information without compromising their privacy. We recognized the importance of leveraging advanced encryption techniques and blockchain technology to create a platform that prioritizes user confidentiality and data security.

## What it does

ProDoc is a secure document editor that allows users to write and share documents anonymously. Users can store sensitive information such as passwords and confidential data, knowing that their documents are encrypted and protected from unauthorized access. The platform leverages Zero-Knowledge Proof (ZKP) encryption to ensure that only authorized users can access their documents, while maintaining anonymity and privacy.

## How we built it

We built ProDoc using a combination of advanced encryption techniques, blockchain technology, and web development tools. The frontend of the application was developed using Noir for writing and generating ZKPs, while everything runs locally in the browser. The backend was implemented using Node.js and MongoDB for data storage. We also integrated wallet signatures for authentication and a mixture of AES encryption and MetaMask's decryption features for enhanced security.

## Challenges we ran into

Throughout the development process, we encountered several challenges, including:

- Implementing advanced encryption techniques and ensuring data security
- Integrating blockchain technology and smart contracts into the application
- Optimizing performance and scalability while maintaining user privacy
- Addressing technical limitations and constraints of the chosen technologies
- Overcoming time constraints and resource limitations during development

## Accomplishments that we're proud of

Despite the challenges we faced, we're proud to have accomplished:

- Successfully implementing robust encryption techniques to ensure user privacy and data security
- Integrating blockchain technology to enhance the transparency and trustworthiness of the platform
- Creating a user-friendly and intuitive interface for seamless document editing and sharing
- Establishing a secure and anonymous platform that empowers users to store and share sensitive information confidently

## What we learned

Through the development of ProDoc, we gained valuable insights into:

- Advanced encryption techniques and their application in data security
- Blockchain technology and its potential to revolutionize document storage and sharing
- User interface and experience design for secure and intuitive user interactions
- Project management and collaboration in a distributed development environment

## What's next for prodoc

Looking ahead, we plan to:

- Expand ProDoc's functionality to support larger documents and additional file formats
- Enhance collaboration features to allow multiple users to edit and share documents securely
- Integrate additional encryption methods and security measures to further enhance data protection
- Explore partnerships and collaborations to broaden ProDoc's reach and impact
- Continuously innovate and evolve the platform based on user feedback and emerging technologies









## Running the Project

### Frontend

1. Install the packages with yarn:

```
yarn
```

2. Start the development node with:

```
npm run node
```

3. Run the frontend with:

```
yarn dev
```

### Backend

1. Install the packages with yarn:

```
yarn
```

2. Run the backend with:

```
yarn dev
```

### Environment Variables

Be sure to use environment variables for your application database, contract address, and more.

1. Frontend env:

```
VITE_API_URL=http://localhost:3000/api
VITE_APP_CONTRACT_ADDRESS=0x0E5438f1f3aa7454b7C3496E9E276f19Acfb3FCc
VITE_APP_ENV=localVITE_APP_ENV
```

2. Backend env:

```
MONGODB_URI=...
MONGODB_DB=zkpaper
BACKEND_PORT=3001
SECRET_KEY=...
```