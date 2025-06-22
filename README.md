# 🎬 ALX Project: 0x14 – Movies Database API Integration

Welcome to **alx-project-0x14**, a project designed to explore and integrate the MoviesDatabase API for dynamic movie content retrieval.

---

## 📚 API Overview

The **MoviesDatabase API** provides access to extensive metadata about movies, TV shows, and actors. It includes features such as:

- Movie and TV title listings
- Title search functionality
- Actor profiles and filmographies
- Trending and popular title tracking
- Access to posters, ratings, and detailed descriptions

---

## 🧾 Version

**Current API Version:** `v2`

This version supports enhanced filtering, better structured responses, and expanded search capabilities.

---

## 🔌 Available Endpoints

| Endpoint                       | Description                                    |
|-------------------------------|------------------------------------------------|
| `/titles`                     | Retrieve a list of movies or TV titles         |
| `/titles/{titleId}`           | Get detailed information for a specific title  |
| `/titles/search/title`        | Search for titles using keywords               |
| `/actors`                     | List popular actors with basic information     |
| `/actors/{actorId}`           | Fetch details about a specific actor           |
| `/titles/trending`            | Get currently trending titles                  |

---

## 🔄 Request and Response Format

**Request Example:**

```http
GET /titles/search/title?title=Inception
Headers:
  X-RapidAPI-Key: YOUR_API_KEY
  X-RapidAPI-Host: moviesdatabase.p.rapidapi.com
