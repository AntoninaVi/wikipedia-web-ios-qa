# Wikipedia iOS Test Cases

## TC-IOS-01 — Save an article

**Precondition:** Wikipedia app is open and network connection is available.

**Steps:**
1. Open an article.
2. Save the article.
3. Open saved articles.

**Expected result:**
The article is displayed in saved articles.

**Status:** Not Run

---

## TC-IOS-02 — Open saved article offline

**Precondition:** An article has been saved.

**Steps:**
1. Close the application.
2. Disable network connection.
3. Relaunch the application.
4. Open saved articles.
5. Open the previously saved article.

**Expected result:**
The saved article is available offline.

**Status:** Not Run

---

## TC-IOS-03 — Preserve article after backgrounding

**Steps:**
1. Open an article.
2. Move the application to background.
3. Return to the application.

**Expected result:**
The previously opened article remains displayed.

**Status:** Not Run
