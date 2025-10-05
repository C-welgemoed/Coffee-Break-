# Coffee Break ☕

> A learning project exploring full-stack development with React, real-time features, and third-party API integrations.

##  About This Project

Coffee Break is a **personal learning project** I built to deepen my understanding of modern web development, specifically focusing on:

- Building complex React applications with state management
- Integrating multiple third-party services and APIs
- Implementing real-time features and background jobs
- Working with cloud services and serverless architecture
- Creating a complete full-stack application from scratch

This project represents my journey in learning how to architect and build a production-ready social media platform using the MERN stack and modern development tools.

** [View Live Demo](https://coffee-break-zeta.vercel.app)**

---

##  Learning Objectives

Through building Coffee Break, I gained hands-on experience with:

### Frontend Development
- **React 18** - Component architecture, hooks, and modern patterns
- **Redux Toolkit** - Complex state management across the application
- **React Router** - Client-side routing and protected routes
- **Tailwind CSS** - Utility-first CSS and responsive design
- **Real-time UI Updates** - Handling SSE streams in React

### Backend Development
- **Node.js & Express** - RESTful API design and middleware
- **MongoDB & Mongoose** - Database modeling and relationships
- **Authentication** - Implementing secure user authentication
- **File Uploads** - Handling multipart form data with Multer
- **Server-Sent Events** - Real-time communication patterns

### Third-Party Integrations
- **Clerk** - Understanding OAuth and authentication services
- **ImageKit** - CDN integration and media optimization
- **Brevo** - Transactional email services and templates
- **Inngest** - Background job processing and scheduled tasks

### DevOps & Deployment
- **Vercel** - Serverless deployment for frontend and backend
- **MongoDB Atlas** - Cloud database management
- **Environment Configuration** - Managing secrets and configs
- **CI/CD** - Automated deployments from Git

---
##  Features Built

###  Main Feed & Stories


<img width="1904" height="1094" alt="Screenshot 2025-10-03 114232" src="https://github.com/user-attachments/assets/e9a8cb25-136a-494a-a96b-3f49608c768f" />

The main feed is where users see all their content in one place:

- **24-Hour Stories** - Ephemeral content that disappears after 24 hours
- **Create Story** - Easy-access button to create new stories
- **Post Feed** - Chronological feed from connections
- **Sponsored Content** - Integrated advertisement sidebar
- **Message Contacts** - Quick access to recent conversations with unread message indicators

###  Story Creation & Viewing
##  Create Story UI
<img width="1441" height="1077" alt="Screenshot 2025-10-03 114219" src="https://github.com/user-attachments/assets/05158223-370f-4c90-8ca1-6f1649e5c85a" />

One of the challenging features to implement was the story system:

- **Text Stories** - Customizable text with multiple background color options
- **Media Stories** - Upload images or videos with automatic optimization
- **Interactive Viewer** - Fullscreen story viewer with tap-to-advance navigation
- **Auto-Advance** - Stories automatically progress after viewing
- **24-Hour Auto-Deletion** - Background jobs remove expired stories
  
##  Story image view

<img width="1912" height="957" alt="Screenshot 2025-10-03 114451" src="https://github.com/user-attachments/assets/4a9187f3-9ced-47bc-8943-988d99421750" />
##  story Text view

<img width="1919" height="1075" alt="Screenshot 2025-10-03 114438" src="https://github.com/user-attachments/assets/f011a115-8c7d-4ee5-81dc-5803e12d7e51" />

The story viewer implements:
- Progress bars showing viewing progress
- Tap left/right to navigate between stories
- User profile display at the top
- Smooth transitions between stories

###  Real-time Messaging
##  Real time messages
<img width="1916" height="1024" alt="Screenshot 2025-10-05 234538" src="https://github.com/user-attachments/assets/32ff4ebf-af36-4d76-a765-4d454f4aa04c" />

Implemented using Server-Sent Events (SSE):

- **Live Message Delivery** - Messages appear instantly without page refresh
- **Message History** - Complete conversation timeline
- **Media Sharing** - Send and receive images within chats
- **Read Receipts** - Track message read status
- **Clean UI** - Modern chat interface with user avatars

###  Connections Management
##  connections dasboard (following tab)
<img width="1270" height="655" alt="Screenshot 2025-10-05 234736" src="https://github.com/user-attachments/assets/c5bc3edc-60fe-46b1-8b65-7e99000f3884" />
##  connections dasboard (follower tab)

<img width="1197" height="754" alt="Screenshot 2025-10-05 234725" src="https://github.com/user-attachments/assets/fb7a0708-e4d2-4a1d-b861-34920a6d005e" />
##  connections dasboard (connecitons tab)

<img width="1915" height="1020" alt="Screenshot 2025-10-05 234708" src="https://github.com/user-attachments/assets/dbc7e112-9b19-45e1-abef-fa6469497d40" />

A comprehensive connection system with multiple relationship types:

- **Connections** - Mutual connections (like friends)
- **Followers** - Users who follow you
- **Following** - Users you follow
- **Pending Requests** - Incoming connection requests to accept/reject


Each connection shows:
- User profile information and bio
- Quick action buttons (View Profile, Message)
- Connection status indicators
- Follow/Unfollow functionality

###  User Discovery
##  Discover Dashboard after search

<img width="1256" height="1071" alt="Screenshot 2025-10-03 114024" src="https://github.com/user-attachments/assets/983fe90d-41a3-4a5c-aa46-061e09a40aef" />


Search and discover new users to connect with:

- **Smart Search** - Find users by name, username, bio, or location
- **User Cards** - Clean profile previews with essential information
- **Follower Counts** - See user popularity metrics
- **Quick Actions** - Follow/Unfollow directly from discovery
- **Real-time Status** - See if you're already following someone

###  Profile Management
##  profile  page view
<img width="1560" height="945" alt="Screenshot 2025-10-03 114134" src="https://github.com/user-attachments/assets/9ca73d77-183e-425f-b7c5-ac1c3c24cc2c" />
##  edit profile view
<img width="649" height="922" alt="Screenshot 2025-10-05 235308" src="https://github.com/user-attachments/assets/1929ef81-3970-4901-a3e5-9d9481bb23ff" />


##  Comprehensive profile system with:

- **Customizable Header** - Upload cover photo and profile picture
- **User Statistics** - Display posts, followers, and following counts
- **Bio & Location** - Personal information display
- **Content Tabs** - Organized view of Posts, Media, and Likes
- **Edit Profile** - Easy access to profile customization

### ✍ Post Creation
##  Created post can be seen on the Feeds
<img width="1903" height="1069" alt="Screenshot 2025-10-03 114417" src="https://github.com/user-attachments/assets/2ad23a55-3de3-4786-8f57-117ccffc9f77" />
##  Create post page
<img width="1765" height="1093" alt="Screenshot 2025-10-03 114354" src="https://github.com/user-attachments/assets/1878fca7-d7be-44ec-abee-8fbc4819e384" />


Simple yet powerful post creation:

- **Rich Text** - Create posts with text content
- **Multiple Images** - Upload up to 4 images per post
- **Hashtag Support** - Automatic hashtag detection and formatting
- **Preview** - See how your post will look before publishing
- **Author Display** - Profile picture and username shown prominently

###  Background Jobs (Inngest)
##  INNGEST Runs dashboard 
<img width="1894" height="889" alt="Screenshot 2025-10-03 114743" src="https://github.com/user-attachments/assets/409abaee-5f34-4505-b614-decfb38ac63f" />

Learned to implement reliable background job processing:

- **Story Auto-Deletion** - Scheduled deletion after 24 hours
- **Email Notifications** - Connection requests and message digests
- **Daily Digests** - Automated unseen message summaries
- **User Sync** - Synchronization with Clerk authentication
- **Event-Driven Architecture** - Triggered by application events

---

##  Technology Stack

### Frontend
```
React 18, Redux Toolkit, React Router v6
Tailwind CSS, Lucide React, React Hot Toast
```

### Backend
```
Node.js, Express.js
MongoDB, Mongoose
Multer (File Uploads)
```

### Third-Party Services
```
Clerk - Authentication
ImageKit - Media CDN
Brevo - Email Service
Inngest - Background Jobs
MongoDB Atlas - Database Hosting
Vercel - Application Hosting
```

---

##  Architecture & Design Decisions

### Why Server-Sent Events?
I chose SSE over WebSockets for real-time messaging to:
- Learn unidirectional real-time communication
- Reduce server complexity (no WebSocket server needed)
- Work better with serverless deployments on Vercel
- Simplify client-side implementation

### Why Multiple Services?
Instead of building everything from scratch, I integrated various services to:
- Learn how to work with third-party APIs
- Understand authentication flows (Clerk)
- Handle media at scale (ImageKit)
- Implement reliable email delivery (Brevo)
- Process background jobs efficiently (Inngest)

### Database Design
```
Users → Posts (One-to-Many)
Users → Stories (One-to-Many, TTL: 24h)
Users → Messages (Many-to-Many)
Users → Connections (Many-to-Many with status)
```

---

##  Key Learning Highlights

### 1. Real-time Messaging Implementation

Learning how to maintain persistent SSE connections and handle real-time data flow:

```javascript
// Server-side SSE connection management
const connections = {};

export const sseController = (req, res) => {
    const { userId } = req.params;
    
    res.setHeader('Content-Type', 'text/event-stream');
    res.setHeader('Cache-Control', 'no-cache');
    res.setHeader('Connection', 'keep-alive');
    
    connections[userId] = res;
    
    // Cleanup on disconnect
    req.on('close', () => {
        delete connections[userId];
    });
};
```

### 2. Background Job Orchestration

Using Inngest to handle scheduled tasks like story deletion and email digests:

```javascript
// Auto-delete stories after 24 hours
const deleteExpiredStory = inngest.createFunction(
    { id: "delete-expired-story" },
    { event: "app/story.delete" },
    async ({ event }) => {
        await Story.findByIdAndDelete(event.data.storyId);
    }
);
```

### 3. Complex State Management

Managing global state for users, connections, and messages using Redux Toolkit:

```javascript
// Redux slice for user connections
const connectionsSlice = createSlice({
    name: 'connections',
    initialState: {
        connections: [],
        followers: [],
        following: [],
        pending: []
    },
    reducers: {
        setConnections: (state, action) => {
            state.connections = action.payload;
        },
        // ... other reducers
    }
});
```

### 4. File Upload and Media Handling

Integrating Multer for uploads and ImageKit for optimization:

```javascript
// Multer configuration for handling uploads
const storage = multer.diskStorage({
    destination: './uploads/',
    filename: (req, file, cb) => {
        cb(null, Date.now() + path.extname(file.originalname));
    }
});

// ImageKit upload with optimization
const response = await imageKit.upload({
    file: fileBuffer,
    fileName: file.originalname,
    useUniqueFileName: true
});
```

---

## 📊 Project Statistics


- **Components Created**: 25+
- **API Endpoints**: 20+
- **Third-Party Services**: 6
- **Database Models**: 5

---

##  Challenges & Solutions

### Challenge 1: Real-time Message Delivery
**Problem**: Implementing real-time chat without WebSockets  
**Solution**: Used Server-Sent Events for unidirectional streaming, maintaining connection pool on server

### Challenge 2: Story Auto-Deletion
**Problem**: Deleting stories exactly 24 hours after creation  
**Solution**: Integrated Inngest for reliable background job scheduling

### Challenge 3: Image Optimization
**Problem**: Large image files causing slow load times  
**Solution**: Integrated ImageKit CDN with automatic WebP conversion

### Challenge 4: Email Deliverability
**Problem**: Transactional emails going to spam  
**Solution**: Used Brevo with verified domain and professional templates

### Challenge 5: State Management Complexity
**Problem**: Prop drilling and complex state updates  
**Solution**: Implemented Redux Toolkit for centralized state management

### Challenge 6: Recent Messages Navigation & Display
**Problem**: Displaying recent message previews with unread indicators in the sidebar while maintaining separate full conversation views. Needed to show the latest message from each conversation, track unread counts, and navigate to the complete chat history without duplicating SSE connections or data fetching logic.

**Solution**: Implemented a dual-component architecture with separated data concerns:
RecentMessages Component: Fetches only received messages ```(Message.find({ to_user_id: userId }))``` , displays connection-based previews using ```getDisplayInfo()``` to match messages with connections, listens to SSE for real-time updates, and uses React Router ```<Link>``` for navigation to ```/messages/:userId```
ChatBox 
***Component***: Fetches complete bidirectional conversation history when URL parameter changes, marks messages as seen, and maintains separate SSE connection for real-time updates
Smart State Updates: Filters duplicate conversations in real-time by removing existing messages from the same sender before adding new ones to the top of the list
Connection-First Approach: Iterates through user connections and finds corresponding messages, ensuring all connections are displayed even without message history. 


---

## What I Learned

### Technical Skills
- ✅ Building scalable React applications with proper architecture
- ✅ Implementing authentication and authorization flows
- ✅ Working with NoSQL databases (MongoDB) and data modeling
- ✅ Integrating multiple third-party APIs and services (Clerk, Inngest, ImageKit, MongoDB, Brevo)
- ✅ Deploying full-stack applications to production (Vercel)
- ✅ Handling real-time data and background jobs 
- ✅ Responsive design and modern UI/UX patterns

### Best Practices
- ✅ Environment variable management and security
- ✅ Error handling and user feedback
- ✅ API design and RESTful conventions
- ✅ Code organization and component structure
- ✅ Git workflow and version control
- ✅ Documentation and code comments

### Soft Skills
- ✅ Breaking down complex features into manageable tasks
- ✅ Debugging and problem-solving strategies
- ✅ Reading documentation effectively (3rd Party Services integration)
- ✅ Managing project scope and timeline
- ✅ Learning from errors and iterations

---

##  Future Improvements

If I continue this project, I'd like to explore:

- [ ] **Comment System** - Add threaded comments on posts
- [ ] **Push Notifications** - Browser notifications for new messages
- [ ] **Advanced Search** - Elasticsearch integration
- [ ] **Analytics Dashboard** - User engagement metrics
- [ ] **Dark Mode** - Theme switching capability
- [ ] **Mobile App** - React Native version

---

## Acknowledgments

Special thanks to the creators and maintainers of:

- **Clerk** - Made authentication incredibly simple
- **ImageKit** - Powerful media optimization without backend complexity
- **Inngest** - Reliable background job processing
- **Brevo** - Professional email service with great documentation
- **Vercel** - Seamless deployment experience
- **MongoDB** - Flexible database for rapid development

---


**Built as a learning project** | *The full Project is in a Private repository* |

*"The best way to learn is by building."*
