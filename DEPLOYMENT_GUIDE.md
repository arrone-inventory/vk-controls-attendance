# VK Controls Attendance Portal – Deployment Guide

## 🚀 Quick Deployment to Netlify (Free)

### Option 1: One-Click Deploy (Easiest)
1. **Create a GitHub account** (if you don't have one): https://github.com/signup
2. **Create a new repository** and upload these files:
   - `index.html` (the main attendance portal)
   - `netlify.toml` (configuration)
   - `README.md`

3. **Go to Netlify**: https://app.netlify.com/signup
4. **Click "Connect from Git"** → Select your GitHub repo
5. **Deploy** (takes ~2 minutes)
6. **You get a live URL** like `https://vk-controls-attendance.netlify.app`

### Option 2: Manual Upload to Netlify
1. Go to https://app.netlify.com
2. Drag and drop `index.html` into the browser
3. **Done!** You have a live URL in 10 seconds

### Option 3: Deploy to Vercel (Alternative)
1. Go to https://vercel.com/signup
2. Upload or connect your GitHub repo
3. Click Deploy
4. Get a URL like `https://vk-controls-attendance.vercel.app`

---

## 🔐 Security Checklist Before Going Live

- [ ] **Change the admin password** (default: demo123 → something strong)
- [ ] **Test login** with both admin and staff accounts
- [ ] **Enable HTTPS** (automatic on Netlify/Vercel)
- [ ] **Remove test data** if needed (Backup → Restore empty database)
- [ ] **Brief your team** on password security
- [ ] **Share the URL** only with authorized staff

---

## 📱 Access Instructions for Your Team

### Admin Access
- **URL**: `https://your-domain.netlify.app`
- **Username**: admin
- **Password**: [Your chosen password]
- **Can**: View all staff, set rules, approve leave, view audit logs

### Staff Access
- **URL**: Same as admin
- **Mobile**: [Staff phone number]
- **Password**: `staff123` (or custom)
- **Can**: Check in/out with GPS & selfie, submit reports, request leave

---

## 🔄 Ongoing Features

### Data Backup
- **Admin Dashboard** → Backup section → "Download Full Backup"
- Do this weekly and save to your computer
- Restore anytime if browser data is cleared

### Updates
- To update the app with new features:
  1. Update `index.html`
  2. Re-deploy to Netlify/Vercel
  3. No data loss (stored in browser storage locally per person)

### Integration with Audit Tracker
```
Daily Flow:
1. Staff check in via Attendance Portal
2. Admin exports attendance CSV
3. Admin can then link to audit reports
4. Format: [Date, Staff, Outlet, Check In, Check Out, Status]
```

---

## 📊 Multi-Device Usage

**Important**: Data is stored **locally in each person's browser**.
- Admin on laptop sees different data than admin on phone
- Solution: Use the same device for admin tasks, or
- Export/Restore backups across devices

For shared team access, consider a backend database upgrade in the future.

---

## ⚠️ Common Issues

### "My data disappeared"
- → Did you clear browser cache? Restore from backup.
- → Using different device? Browser storage is device-specific.

### "Password not working"
- → Admin password is case-sensitive
- → Staff passwords are the phone number + password you set

### "GPS not working on field"
- → Staff must allow location permission
- → Works best on mobile (iPhone/Android)
- → Requires HTTPS (automatic on Netlify)

---

## 🎯 Next Steps

1. ✅ Deploy using Option 1 or 2 above
2. ✅ Change admin password
3. ✅ Test staff login on a phone
4. ✅ Set Shift Start time in Settings
5. ✅ Export first day's attendance

---

**Live URL**: Your Netlify/Vercel domain will be shown after deployment.
**Support**: If issues, check browser console (F12 → Console tab) for error messages.
