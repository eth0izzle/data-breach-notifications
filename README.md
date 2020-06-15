# Data Breach Notifications

This repository serves as a collection of data breach notifications. It is not meant to analyse the notifications themselves but merely serve as an archive.

## Contributing

You are very welcome to contribute to this project via a pull request. To ensure data remains in a consistent format and can be easily processed, it must be presented in the following format:

1. Create a new folder with the format `YYYY-mm-dd-organisation` where YYYY-mm-dd is the date of notification in ISO 8601 format and `organisation` is the lowercase name of the company affected. For example, `2020-05-21-easyjet`.

2. Each folder should contain a minimum of three files:

   * **notification.txt**: a plain text file containing just the notification message itself. All surrounding images, metadata, etc. should be removed.
   * **email.eml**: a copy of the notifiation e-mail in eml format, including headers. You should ensure you have stripped any personally identifiable information by find and replace your name with `REDACTED`, your e-mail with `redacted@redacted.com`, and any special links, i.e. login
   * **capture.[pdf|jpg]**: a screen capture of the notification e-mail including images. You should ensure you have stripped any personally identifiable information.
   
   
