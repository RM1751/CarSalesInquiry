# Cloud Database Setup (Required for cross-device sync)

## Option 1: JSONBin.io (Recommended - Free)

### Step 1: Create Account
1. Go to https://jsonbin.io
2. Click "Sign Up" (free account)
3. Verify your email

### Step 2: Create a Bin
1. Click "Create Bin"
2. Paste this content:
```json
{
  "sliderPhotos": [],
  "carPhotos": {},
  "sliderEnabled": true,
  "sliderSpeed": 5000
}
```
3. Click "Create"
4. Copy the Bin ID (looks like: `65abc1234567890abcdef12`)

### Step 3: Get API Key
1. Click your profile (top right)
2. Go to "API Keys"
3. Copy the "Master Key"

### Step 4: Update admin.html
Replace these lines in admin.html:
```javascript
const BIN_ID = 'YOUR_BIN_ID_HERE';
const API_KEY = 'YOUR_API_KEY_HERE';
```

With your actual values from steps 2 and 3.

### Step 5: Update index.html
Copy the same BIN_ID and API_KEY to index.html

---

## Option 2: Use GitHub Gist (Alternative)

If JSONBin doesn't work, I can set up GitHub Gist instead.

---

## After Setup:
- Photos will be saved to the cloud
- Visible on all devices (mobile, laptop, etc.)
- Auto-save (no manual save button needed)
- When you add a photo, it appears everywhere instantly
