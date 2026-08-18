# VK Controls Attendance Portal v2

A secure, mobile-first attendance management system for multi-outlet operations. GPS verification, selfie capture, daily reports, and audit trails.

## ✨ Features

### Admin Dashboard
- **Real-time metrics**: Active staff, present/absent today, pending reports
- **Staff management**: Add, edit, deactivate staff across outlets
- **Outlet management**: Configure multiple locations with GPS radius
- **Attendance records**: View and export attendance history
- **Leave requests**: Approve/reject employee leave
- **Audit logs**: Complete admin action trail with timestamps
- **Settings**: Configure shift times and reporting rules
- **Backup/Restore**: Secure data backup and recovery

### Employee Mobile App
- **GPS check-in/out**: Capture location for audit compliance
- **Selfie verification**: Photo timestamp for authentication
- **Daily reports**: Submit/track compliance
- **Leave requests**: Request and track approval status
- **Real-time clock**: Large display for field reference
- **Outlet selection**: Flexible multi-location check-in

## 🔐 Security

- **Password hashing**: SHA-256 with salt (CryptoJS)
- **Session tokens**: 8-hour expiry, logout required
- **Audit logging**: Every admin action tracked with timestamp
- **Role-based access**: Admin vs staff permissions
- **Secure storage**: LocalStorage with data encryption-ready

## 🚀 Deployment

### Quick Start (Netlify)
1. Download `index.html` + `netlify.toml`
2. Upload to [Netlify](https://app.netlify.app)
3. Get live URL instantly

**See DEPLOYMENT_GUIDE.md for detailed steps**

## 📱 Browser Support
- Chrome/Chromium 80+
- Safari 13+
- Firefox 75+
- Mobile: iOS 12+, Android 8+

## 💾 Data Storage
- All data stored **locally in browser** (localStorage)
- **No server required** — works completely offline
- Regular backups recommended
- Multi-device sync: Export from one device, restore on another

## 📊 Export Formats
- **CSV**: Attendance records, audit logs
- **JSON**: Full database backup/restore
- Compatible with Excel, Google Sheets

## 🎯 Default Credentials

| Role | Username | Password |
|------|----------|----------|
| Admin | admin | Rs01d@2019 |
| Staff | 9876543210 | staff123 |
| Staff | 9876543211 | staff123 |

⚠️ **Change admin password immediately after deployment**

## ⚙️ Configuration

### Shift Settings (Admin → Settings)
- **Shift Start**: When work day begins (e.g., 09:15)
- **Late After**: Threshold for marking late (e.g., 09:30)
- **Half Day After**: Time for half-day rule (e.g., 12:00)
- **Minimum Hours**: Required daily working hours
- **Weekly Reports Required**: Reports per week per staff

### Staff Setup
- Add staff with name, mobile, role
- Assign to outlets (one or multiple)
- Set work type (Full Time / Part Time)
- Configure weekly work pattern (Daily / Weekly schedules)
- Auto-generate or custom passwords

## 📈 Reporting & Compliance

### Reports Available
- **Daily Attendance**: Present/absent by staff and outlet
- **Attendance Analytics**: Trends, patterns, utilization
- **Leave Audit**: Approval status and matching
- **Audit Trail**: Admin actions with timestamps
- **Compliance**: Late arrivals, missing reports

### Integration with Tracker
```json
{
  "date": "2026-08-18",
  "outlet": "Koramangala",
  "staff": [
    {
      "name": "Vasudevan V",
      "mobile": "9876543210",
      "checkIn": "09:20",
      "checkOut": "18:45",
      "status": "Late",
      "gpsConfirmed": true,
      "selfieConfirmed": true
    }
  ]
}
```

## 🔧 Troubleshooting

### GPS not working?
- Ensure HTTPS (automatic on Netlify)
- Grant location permission on mobile
- Test on actual phone (not desktop emulation)

### Data disappeared?
- Check browser cache isn't cleared
- Restore from backup file
- Use consistent device/browser

### Login issues?
- Admin password is case-sensitive
- Staff username is exact mobile number
- Check CAPS LOCK

## 📝 Version History

**v2.0** (Aug 2026)
- ✅ Password hashing (SHA-256)
- ✅ Session tokens with expiry
- ✅ Comprehensive audit logging
- ✅ Mobile-first responsive design
- ✅ Larger touch targets for field use
- ✅ Admin audit log page
- ✅ Password reset functionality

**v1.0** (Earlier)
- Basic attendance tracking
- GPS and selfie capture
- LocalStorage backup

## 📞 Support

For issues or feature requests:
1. Check the Troubleshooting section above
2. Export audit log (Admin → Audit Log)
3. Take screenshot of error (F12 → Console)
4. Contact your administrator

## 📄 License

Internal use for VK Controls only. All rights reserved.

---

**Ready to deploy?** → See [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md)

