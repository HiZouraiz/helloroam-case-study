# HelloRoam

HelloRoam is an eSIM service that lets travelers buy prepaid mobile data for more than 190 countries and get online by scanning a QR code, without a physical SIM. It is live on iOS and Android and has a 5 out of 5 rating on the App Store.

I worked on HelloRoam as a senior team lead. I led two teams, the mobile app team and the website development team, and I was responsible for delivery on both. I also designed and built the AI engine that handles the product's content, SEO and translation across all 22 languages it supports.

This repository is a case study. Everything here comes from the public app store listings and the public website. The work was done under NDA, so there is no proprietary code or private data in this repo.

## What the product does

Travelers buy a data plan online, scan a QR code, and connect to a local network as soon as they land. It covers more than 190 countries across 199 carrier networks, supports dual SIM so people keep their home number, and includes hotspot sharing. The whole experience is localized into 22 languages.

## What I did

As senior team lead I ran both the mobile and website teams, reviewed the architecture on both sides, and kept delivery moving to the App Store and Play Store. On the engineering side, the piece I owned most directly was the AI content and localization system that the marketing site depends on to publish pages in every supported language.

## The AI content and localization engine

Publishing content by hand in 22 languages is not realistic, so I built a system that takes one piece of source content and turns it into a finished, localized page for each market. From a single input it does the SEO keyword research for each language, translates the content so it reads naturally instead of word for word, generates images that suit each locale, and produces the slug, title and meta description for search. The output is a publish-ready page per language from one source, rather than needing a separate translator, SEO specialist and designer for each one.

## Tech

React Native with Expo and TypeScript for the app, React Navigation, and Redux or Zustand for state. Internationalization across 22 languages. Node.js and REST on the backend. The eSIM activation follows the GSMA SGP.22 QR provisioning flow. The AI engine uses large language models (OpenAI and Anthropic) with LangChain for translation, SEO and image generation.

<!-- Zouraiz: correct any tech detail here that is not exact. -->

## Some of the harder parts

The eSIM activation flow was the trickiest piece on the app side. It goes from purchase to provisioning to QR or manual activation following the GSMA standard, and it had to stay clear for non-technical travelers, with sensible error and retry states. Localizing across 22 languages meant building the i18n layer so copy, currency and date formats adapt per locale from one codebase, with no separate builds. Plan selection also took some care, since users can pick single-country, regional or multi-region plans across more than 190 countries and it can't feel overwhelming. And running two teams meant staying on top of both the app and the site at once.

## Screenshots

Add the public App Store and Play Store screenshots here. They are already public, so they are fine to use.

## Links

- Website: https://helloroam.com
- App Store: add link
- Google Play: add link
