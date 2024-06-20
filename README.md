# Google Images Downloader

## Project Summary

This project is a Python script that allows you to search and download images from Google based on a user-defined keyword and number of images. The images are saved in a specified subfolder, which can be optionally zipped for easy downloading.

## How to Get Your Own API Key and Custom Search Engine (CX)

### 1. Google Cloud Console
1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or select an existing project.
3. Navigate to the **APIs & Services** > **Credentials** page.
4. Click **Create Credentials** and select **API Key**.
5. Copy the generated API key and save it for later use.

### 2. Custom Search Engine
1. Go to the [Custom Search Engine](https://cse.google.com/cse/all) page.
2. Click **Add** to create a new search engine.
3. In the **Sites to search** field, you can specify sites you want to include in the search. To search the entire web, enter `*.`
4. Click **Create**.
5. Go to the **Control Panel** for your search engine and make a note of the **Search engine ID** (CX).

### 3. Set Up Environment Variables
Set your API key and CX as environment variables in your system:
```bash
export GCS_DEVELOPER_KEY='your-api-key'
export GCS_CX='your-cx'
