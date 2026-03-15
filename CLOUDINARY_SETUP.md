# Cloudinary Setup Guide for Rahul Car Sales

## Step 1: Get Your Cloud Name

1. Look at the top-left corner of your Cloudinary dashboard
2. You'll see something like: `dbaduzib2` (this is your cloud name)
3. **Write it down**

## Step 2: Create Upload Preset

1. In your Cloudinary dashboard, click on **"Settings"** (gear icon) in the top right
2. Click on **"Upload"** tab
3. Scroll down to **"Upload presets"** section
4. Click **"Add upload preset"**
5. Fill in these settings:
   - **Preset name**: `rahul_car_sales` (exactly this)
   - **Signing Mode**: Select **"Unsigned"** (IMPORTANT!)
   - **Folder**: Leave blank or type `car_sales`
   - Click **"Save"**

## Step 3: Update admin.html

Once you have your cloud name, I will update the admin.html file with:
- Your actual cloud name
- The upload preset name

## That's it!

After this setup, when you upload photos in admin.html, they will:
- Be stored in Cloudinary cloud
- Be visible to everyone on all devices
- Automatically appear on your main website

---

## What I Need From You:

1. Your Cloudinary Cloud Name (from top-left of dashboard)

Once you give me this, I'll update the code and push it!
