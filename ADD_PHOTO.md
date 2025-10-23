# Adding Your Profile Photo

## Steps to Add Your Photo:

### 1. Prepare Your Image
- **Save your photo** as `profile-photo.jpg`
- **Recommended size**: 400x400 pixels or larger (square aspect ratio)
- **Format**: JPG, PNG, or WebP
- **Quality**: High resolution for best results

### 2. Add to Portfolio
1. **Copy your photo** to the portfolio-website folder
2. **Rename it** to `profile-photo.jpg` (exactly this name)
3. **Place it** in the same folder as `index.html`

### 3. Photo Optimization Tips
- **Face positioning**: Make sure your face is centered and well-lit
- **Background**: Simple or blurred background works best
- **Expression**: Professional, friendly smile
- **Lighting**: Good natural lighting or professional lighting

### 4. CSS Features Added
- ✅ **Circular crop**: Perfect circle shape
- ✅ **Face highlighting**: `object-position: center top` focuses on your face
- ✅ **Hover effect**: Slight zoom on hover
- ✅ **Responsive**: Scales properly on all devices
- ✅ **Professional styling**: Matches the portfolio design

### 5. File Structure
Your portfolio folder should look like this:
```
portfolio-website/
├── index.html
├── styles.css
├── script.js
├── profile-photo.jpg  ← Your photo here
├── README.md
└── other files...
```

### 6. Testing
1. **Refresh your website**: `http://localhost:8001/portfolio-website/`
2. **Check the hero section**: Your photo should appear in the right side
3. **Test responsiveness**: Check on mobile and desktop
4. **Verify quality**: Make sure the image looks sharp

### 7. Alternative Image Names
If you want to use a different filename, update the HTML:
```html
<img src="your-photo-name.jpg" alt="Subin Maharjan" class="profile-photo">
```

### 8. Troubleshooting
- **Image not showing**: Check filename is exactly `profile-photo.jpg`
- **Poor quality**: Use higher resolution image
- **Wrong crop**: Adjust the image before adding it
- **Loading issues**: Make sure file is in the correct folder

## Professional Tips:
- **Use a high-quality headshot**
- **Ensure good lighting on your face**
- **Keep background simple or blurred**
- **Maintain professional appearance**
- **Test on different screen sizes**

Your photo will now be prominently displayed in the hero section, creating a more personal and professional portfolio!
