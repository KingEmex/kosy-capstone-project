# 📑 Use Cases for My Dictionary App

## 1. Look Up a Word
- **Actor**: User  
- **Trigger**: User types a word into the search bar and clicks **Search**  
- **Flow**:
  1. User enters "education".
  2. The app fetches definitions, phonetics, and examples from the Dictionary API.
  3. Results display in a card with options to **Read Aloud** or **Reset**.

## 2. View Search History
- **Actor**: User  
- **Trigger**: User clicks **History** in the bottom navbar.  
- **Flow**:
  1. User sees a list of recently searched words.
  2. Clicking a word expands it to show definitions again.
  3. User can **Remove** an item or **Clear All History**.

## 3. Listen to Word Pronunciation
- **Actor**: User  
- **Trigger**: User clicks **Read 🔊**.  
- **Flow**:
  1. App reads out the word, phonetics, and definitions via text-to-speech.
  2. User can click **Stop** to cancel reading.

## 4. Explore Trending Words
- **Actor**: User  
- **Trigger**: User views the **Trending Searches ticker**.  
- **Flow**:
  1. Words scroll across the screen.
  2. User clicks a trending word.
  3. App performs a search for that word automatically.
