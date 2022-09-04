# Londonderry YSA Blogger

Welcome to your calling as a ward technology specialist! As part of your calling, you will be managing the Londonderry YSA ward website. The ward website is a place where any ward members can go to find information about ward activities.

This is a repository of files and information that will be helpful to you in your calling as you serve to keep the website up to date with the latest announcements and information about the sacrament program. Most of the files here are backup files in case something goes wrong, you'll be able to restore the website to it's former glory.

## Weekly maintenance

As part of your calling, there are two pages of the website you'll need to keep up to date. You should update those pages after the ward council reviews the announcements and sacrament program during ward council on Sunday morning and before sacrament meeting.

You should have access to a "Londerry YSA Ward Program" Google document that the ward council manages. If you don't have access, ask a member of the bishopric for access to that document. The ward council will typically add announcements to the Google document throughout the week and then review it during ward council on Sunday.

You should also have access to the [Blogger website](https://www.blogger.com). Blogger is a blogging platform hosted by Google. If you don't have access, ask a member of the bishopric for access as an admin.

When copy/pasting information from the Google document to the Blogger editor, it is ***highly*** recommended to use `ctrl shift v` (or `cmd shift v` on MacOS) to paste into the Blogger editor. This will paste without formatting, so any formatting from the Google document will be ignored in favor of the Blogger formatting, ensuring that the website looks nice.

### Announcements page

The announcements page has all the announcements for the upcoming week(s).

<!-- TODO: Add more detailed steps to expand upon step 4  -->
To update the announcements page:
1. Navigate to the [Blogger website](https://www.blogger.com).
2. Click on the `New Post` button on the left sidebar.
    - If the `New Post` button is not visible, click on the `Posts` link in the left sidebar.
3. Set the title of the post to be the week range, starting on Sunday.
    - Example: "June 19th - 25th" if Sunday was June 19th.
4. Copy and paste the announcements from the "Londonderry YSA Ward Program" to the post.
5. Click the `Publish` button in the top right corner when you are done.

### Sacrament program page

The sacrament program page has information about the sacrament program.

<!-- TODO: Add more detailed steps to expand upon step 4  -->
To update the sacrament program page:
1. Navigate to the [Blogger website](https://www.blogger.com).
2. Click on the `Pages` link on the left sidebar.
3. Click on the "Sacrament Meeting" page.
4. Copy and paste the program information from the "Londonderry YSA Ward Program" to the post.
5. Click the `Update` button in the top right corner when you are done.

## Files in this repository

### [favicon.png](favicon.png)

This is the [favicon](https://www.w3schools.com/html/html_favicon.asp) for the Blogger website. You can update the favicon under settings on [Blogger](https://www.blogger.com).

### [program-template.html](program-template.html)
<!-- TODO: Add more information about how to use the template -->
This is the template for the sacrament program page.

### [qr-code.png](qr-code.png)
This is the QR code that is on [this page](https://londonderryysa.blogspot.com/p/qr-code.html).

### [theme.xml](theme.xml)

This is the Blogger theme. I took the Soho theme and made some modifications to it to make it look nicer. You can look at the history of changes that have been made [here](https://github.com/Zachatoo/londonderry-ysa-blogger/commits/main/theme.xml).

Instructions on how to restore the theme from backup are [here](#ive-accidently-messed-up-the-theme-how-do-i-revert-back-to-what-it-was).

## FAQ

### When I paste text into the Blogger editor, the formatting looks weird. How do I avoid this?
1. Copy the text using `ctrl c` (or `cmd c` on MacOS). It is recommended to copy as little information as possible.
2. Paste the text using `ctrl shift v` (or `cmd shift v` on MacOS). This will paste without formatting.

### How do I schedule out announcements in advance?
1. Follow steps 1-4 under [announcements](#announcements-page).
2. Click `Published On` on the right sidebar.
3. Select the date and time you would like the announcement to be posted on.
4. Click the `Publish` button in the top right corner.


### I've accidently messed up the theme. How do I revert back to what it was?

1. Download the [theme.xml](theme.xml) file from this repository.
    - If you can't download the file, then you can copy the text from [here](https://raw.githubusercontent.com/Zachatoo/londonderry-ysa-blogger/main/theme.xml) and then create a new .xml file and paste the text into that file using a text editor.
2. Navigate to the [Blogger website](https://www.blogger.com).
3. Click on the `Theme` link in the left sidebar.
4. Click the dropdown next to the `Customize` button.
5. Click `Restore`.
6. Click `Upload` and upload the [theme.xml](theme.xml) file you downloaded in step 1.

### There's too many announcements (posts) on the homepage, how do I fix it?

1. Go to `Layout > Page Body > Blog Posts`.
2. Set `number of pages on main page` to 1.

### How do I generate a new QR code?

You shouldn't need to do this unless you want to change which url you want to QR code to take people to.

1. Look up a "QR code generator".
  - This is the one I used [https://www.qr-code-generator.com/](https://www.qr-code-generator.com/).
2. Paste the url of the page you want the QR code to be for.
3. Download the file (png or jpeg is easiest).
4. Navigate to the [Blogger website](https://www.blogger.com).
5. Go to `Pages > QR Code`.
6. Insert the new QR code image into the document. Remove the old QR code image.
7. Click `Update` to save your changes.