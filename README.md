# StoryLurk

Free Instagram story viewer for public accounts. Watch and download stories, posts, reels and highlights without logging in.

**Website: [storylurk.com](https://storylurk.com)**

## What it does

- Shows a public account's current stories, recent posts and reels, highlights and profile (bio, follower count, full-size profile photo)
- Lets you download any photo or video in full quality
- Takes a username, with or without the @, or a pasted profile link
- Needs no Instagram login, no sign-up and nothing to install
- Works in the browser on phones, tablets and computers
- Keeps your name out of the account's story viewer list

## What it doesn't do

- Private accounts, close-friends stories and subscriber-only posts stay private
- It shows recent posts only, not an account's full history

## Tech stack

- Next.js and React, written in TypeScript
- Tailwind CSS
- Runs on Cloudflare Workers (built with OpenNext), with Workers KV as a short-term cache
- Public Instagram data comes from a third-party data API

## Privacy

StoryLurk only handles public data. It never asks for an Instagram username or password, and it doesn't keep a history of the usernames people search. Public content is cached for a short time so pages load faster: about 30 minutes for stories and up to 24 hours for profile details. Photos and videos load straight from Instagram's servers. The full privacy policy is on the website.

If you own a public account and don't want it on StoryLurk, email support@storylurk.com and it will be blocked.

## About this repository

This repository is StoryLurk's home on GitHub. The website's source code isn't public. Questions and feedback: support@storylurk.com.

StoryLurk is an independent project and isn't affiliated with Instagram or Meta.
