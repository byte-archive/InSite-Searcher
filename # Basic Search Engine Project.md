# Basic Search Engine Project

## Overview
This project is a basic implementation of a search engine for a small set of HTML documents. It indexes the content of these documents and allows users to search through this content using various queries.

## Features
- **Indexing of HTML Documents**: Processes and indexes the content of HTML files.
- **Search Functionality**: Supports searching for single or multiple keywords.
- **Ranking of Search Results**: Ranks results based on the frequency of query terms.
- **Stop Word Filtering**: Excludes common words (stop words) from indexing and searches to enhance relevance.

## Technologies Used
- **Python**: Primary programming language used.
- **Regular Expressions (re module)**: For processing text.
- **Collections Module**: For efficient data handling (e.g., defaultdict).

## How It Works

### Indexing
- The search engine reads HTML files, parsing their content.
- It creates an inverted index mapping terms to the documents containing them.
- Common stop words are excluded from the index to enhance search efficiency.

### Search and Ranking
- Users input search queries when prompted by the script.
- The engine processes queries, removing stop words, and looks for remaining terms in the index.
- Search supports both single and multiple keyword queries.
- Results are ranked based on the frequency of query terms in each document, with higher frequency yielding higher ranks.

## Setup and Execution
1. **Preparation**:
   - Install Python on your system.
   - Place HTML documents in a designated directory.
2. **Execution**:
   - Run `search_engine.py` (adjust with the actual name of your script).
   - Input search queries as prompted.
3. **Output**:
   - Results are displayed in the console and logged in `output.txt`.

## Project Structure
- `search_engine.py`: The main Python script.
- `output.txt`: File where the search results are logged.
- HTML Documents: Set of HTML files used for indexing and search.

## Testing
The engine has been tested with:
- Single and multiple keyword queries.
- Queries containing stop words.
- Empty queries.

## Future Scope
- Implement advanced ranking algorithms.
- Extend to handle larger and more complex documents.
- Enhance HTML tag and metadata processing.

## Contact
For queries or suggestions, please contact pkshirs1@stevens.edu.

