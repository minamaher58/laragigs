# LaraGigs app

An app for listing Laravel gigs/jobs.

![Alt text](/public/images/screen.png "LaraGigs")


### File Uploading
When uploading listing files, they go to "storage/app/public". Create a symlink with the following command to make them publicly accessible.
```
php artisan storage:link
```