import qrcode

# Your profile website link
url = "https://vidyashreem46.github.io/profile-website/"

# Create QR code
qr = qrcode.QRCode(
    version=3,
    error_correction=qrcode.constants.ERROR_CORRECT_H,
    box_size=10,
    border=4
)
qr.add_data(url)
qr.make(fit=True)

# Save as PNG
img = qr.make_image(fill_color="black", back_color="white")
img.save("vidyashree_profile_qr.png")

print("QR code created! Open this image and scan it.")

