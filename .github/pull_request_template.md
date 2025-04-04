## 🚔 Crime Stoppers App – Code Review Checklist

### 🧠 Code Quality & Standards
- [ ] Code follows team naming conventions and project structure
- [ ] No unnecessary commented-out or unused code
- [ ] Logic is modular, easy to follow, and reusable where possible

### ⚙️ Functionality
- [ ] New or updated features work as described
- [ ] No regression issues introduced to existing features
- [ ] Error handling is present and meaningful

### 🧪 Testing
- [ ] Unit tests are added/updated (Jasmine)
- [ ] Integration tests (Cypress) are in place if applicable
- [ ] Appium tests are considered for new UI flows
- [ ] Manual testing steps (if applicable) are described in PR

### 🔐 Security & Validation
- [ ] Input validation and sanitation are implemented
- [ ] API endpoints are protected appropriately (e.g., logged-in user restrictions)
- [ ] Sensitive info (e.g., credentials) is not hardcoded or logged

### 📱 Frontend (Ionic/Angular)
- [ ] Forms use Reactive Forms with proper validation
- [ ] UI follows Material Design or app-wide style guide
- [ ] Navigation and state management behave correctly across tabs/pages
- [ ] Responsive design and accessibility are considered

### 🛠️ Backend (Node.js/Express)
- [ ] REST APIs follow consistent patterns (GET, POST, etc.)
- [ ] Proper use of middleware (e.g., auth, logging)
- [ ] MongoDB/DB queries are optimized and secure

### 📁 Project Hygiene
- [ ] Only necessary files are included in the PR
- [ ] No environment files or debug logs committed (e.g., `.env`, `console.log`)
- [ ] Code is formatted (Prettier/ESLint, if applicable)

### 📄 Documentation & PR Info
- [ ] PR description clearly explains changes
- [ ] Related Trello cards, issues, or user stories are linked
- [ ] Screenshots, demo videos, or GIFs are included (if applicable)
- [ ] Reviewer instructions are provided

---

**Ready for Review?**  
Tag teammates when you're done ✅
