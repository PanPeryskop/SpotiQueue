# SpotiQueue

SpotiQueue is a Python application that allows Spotify users to queue multiple playlists. The application uses the Spotify API to extract user playlists and add them to the queue.

## Features

- Extract playlists from a user's Spotify profile
- Extract playlists from a provided Spotify URL
- Add playlists to the queue

## Before you install

Before you can use SpotiQueue, you need to create a Spotify Developer application to get your `client_id`, `client_secret`, and `redirect_uri`. Here's how you can do it:

1. Go to the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).
2. Log in with your Spotify account.
3. Click on 'Create an App'.
4. Fill in the 'Name', 'Description' and redirect_uri (I recommend using http://localhost:3000/) for your new app, then click 'Create'.
5. On the next page, you will see your `client_id` and `client_secret`. You will need these to authenticate your application.
6. Click on 'Edit Settings'.
7. In the 'Redirect URIs' field, enter the URI where you want Spotify to redirect you after a successful login.
8. Click 'Save'.

## Installation

1. Go to the release section of this repository. [Current release.](https://github.com/PanPeryskop/SpotiQueue/releases/tag/v1.1)
2. Click on **SpotiQueue.zip**. Download will start automatically.
3. Extract the zip file.
4. Open the extracted folder and run `SpotiQueue.exe`.

## Usage

1. Run the `SpotiQueue.exe` to start the application.
2. The application will ask you to enter your `client_id`, `client_secret`, and `redirect_uri`. Enter the values from the Spotify Developer Dashboard.
3. Select the source of the playlists (from profile or from URL).
4. If you select "From Profile", the application will display your playlists and you can select which ones to add to the queue.
5. If you select "From URL", you will need to provide the URL of the Spotify playlist you want to add to the queue.
6. The application will then add the selected playlists to your Spotify queue.

Enjoy your music!
