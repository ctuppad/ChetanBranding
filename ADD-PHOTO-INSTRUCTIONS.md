# 📸 Add Your Photo

To complete the update, please add your professional headshot:

## Step 1: Copy Your Photo

```bash
cp "/Users/cappasahebtuppa/Desktop/Personal/Chetan Photos/568C8D8B-04F3-4BB8-8B40-9505914022E7_1_105_c.jpeg" ~/ChetanBranding-update/profile-photo.jpg
```

Or manually:
1. Navigate to: `/Users/cappasahebtuppa/Desktop/Personal/Chetan Photos/`
2. Copy: `568C8D8B-04F3-4BB8-8B40-9505914022E7_1_105_c.jpeg`
3. Paste into: `~/ChetanBranding-update/`
4. Rename to: `profile-photo.jpg`

## Step 2: Test Locally

```bash
open ~/ChetanBranding-update/index.html
```

## Step 3: Commit and Push

```bash
cd ~/ChetanBranding-update
git add profile-photo.jpg
git commit -m "Add professional headshot"
git push origin main
```

Your site will be live in 1-2 minutes at: https://ctuppad.github.io/ChetanBranding/
