<p align="center">
  <img src="https://pub-ac805a7c7b0849ca8cf86ae70f240bda.r2.dev/our-internal-files-erpli/marketing/logo.png" alt="Erpli Logo" width="120">
</p>

<h1 align="center">Erpli Wave</h1>

<p align="center">
  <strong>Production-ready distribution for simple, fast deployment.</strong>
</p>

<p align="center">
  Download the pre-built files and upload them to your hosting provider,<br>
  or connect this repository directly to your domain.
</p>

Overview

Erpli Wave is provided as a ready-to-deploy production build.

There is no need to install dependencies, run a build command, or configure a local development environment if your goal is simply to deploy the application.

The final production distribution is available at:

public/dist

The contents of this directory can be served directly from your web hosting environment.

Quick Deployment

Option 1 — Download and Upload

For a traditional hosting setup:

Download or clone this repository.

Open the public/dist directory.

Upload the contents of public/dist to your hosting provider's web root.

Connect or point your domain to that hosting environment.

Open your domain and verify that Erpli Wave loads correctly.

Common web-root directories include:

public_html/
www/
htdocs/

Note: Upload the files inside public/dist to the directory served by your domain, unless your hosting provider allows you to configure public/dist itself as the document root.

Repository-Based Deployment

If your hosting platform supports deployment directly from a Git repository, you can connect this public repository instead of downloading and uploading the files manually.

Configure the platform to publish or serve:

public/dist

as the site's publish directory, output directory, or document root, depending on the terminology used by your hosting provider.

This is generally the easiest option when you want future repository updates to be reflected through your normal deployment workflow.

Directory Structure

A simplified deployment structure looks like this:

repository/
└── public/
    └── dist/
        ├── index.html
        ├── assets/
        └── ...

public/dist should be treated as the production distribution directory.

Before Going Live

After deployment, verify that:

Your domain points to the correct hosting environment.

index.html is accessible from the site root.

Static assets load correctly.

HTTPS/SSL is enabled for your domain.

Your hosting provider is serving the contents of public/dist.

Important

public/dist contains the ready-to-deploy version of Erpli Wave.

For a standard deployment, you do not need to rebuild the application. Simply deploy the distribution files or configure your hosting platform to serve this directory.

<p align="center">
  <img src="https://pub-ac805a7c7b0849ca8cf86ae70f240bda.r2.dev/our-internal-files-erpli/marketing/logo.png" alt="Erpli" width="60">
</p>

<p align="center">
  <strong>Erpli Wave</strong><br>
  Ready to deploy. Simple to host.
</p>
