User Interface: Focused on creating an intuitive and visually appealing user interface.
Back-End Integration
Firebase Authentication: Integrated Firebase for secure user authentication and real-time database management.
Database Management: Used Firebase to manage and store appointment data efficiently.
Project Management
Feature Development: Developed functional features while ensuring an enhanced user experience.
Usability Optimization: Aimed to optimize usability and efficiency through careful planning and implementation.



---

### **Run App**
1. **Navigate to the Project Directory**:
   ```bash
   cd /path/to/your/app
   ```

2. **Install Dependencies**:
   Ensure all dependencies are installed from `package.json`:
   ```bash
   npm install
   ```
   
   If there is no `package.json` file, you cannot install dependencies. Create one using:
   ```bash
   npm init -y
   ```
   Then, manually add the dependencies using:
   ```bash
   npm install <package-name>
   ```

   Global Installation of a Package**:
   To install a package globally (not in `node_modules` but for system-wide use):
   ```bash
   npm install -g <package-name>
   ```

3. **Start the Server**:
   If you have a `start` script defined in your `package.json` (e.g., `"start": "node server.js"`):
   ```bash
   npm start
   ```
   Alternatively, run the main server file directly:
   ```bash
   node server.js
   ```

4. **View the App**:
   Open a browser and go to `http://localhost:<port>` (default is usually `3000`).

---

### **Firebase**
1. **Install Firebase CLI**:
   If not already installed:
   ```bash
   npm install -g firebase-tools
   ```

2. **Log in to Firebase**:
   Authenticate with your Firebase account:
   ```bash
   firebase login
   ```

3. **Initialize a Firebase Project**:
   Run the initialization command and follow the prompts:
   ```bash
   firebase init
   ```
   - Select features (e.g., Hosting, Firestore, Functions, etc.).
   - Specify the project directory and configurations.

4. **Serve the Firebase Project Locally**:
   To serve Firebase Hosting locally:
   ```bash
   firebase serve
   ```
   Or, for Firebase Hosting specifically:
   ```bash
   firebase hosting:serve
   ```

5. **Deploy the Firebase Project**:
   Deploy your Firebase project to the cloud:
   ```bash
   firebase deploy
   ```

6. **View Hosting URL**:
   After deployment, you’ll receive a hosting URL like `https://<project-id>.web.app`.

---

### Summary
- **Node.js**: `npm install` → `npm start` or `node server.js`
- **Firebase**: `firebase login` → `firebase init` → `firebase serve` → `firebase deploy`
