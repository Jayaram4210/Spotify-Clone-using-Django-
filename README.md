**Project Title:**
Django Music Library Manager-Spotify Clone

**Description:**  
This is a Django-based web application that allows users to manage a personal music library. Users can upload songs, organize them by artist or genre, and play previews directly from the browser. The app uses Bootstrap for a responsive UI and supports media file handling through Django’s built-in tools.

**Tech Stack:**  
- Django  
- Python  
- Bootstrap  
- HTML/CSS  
- SQLite or PostgreSQL  
- JavaScript 

**Installation Instructions:**  
1. Clone the repository:  
   git clone https://github.com/Jayaram4210/Music-Library-Django.git  
   cd Music-Library-Django

2. Create a virtual environment:  
   python -m venv venv  
   On Windows: venv\Scripts\activate  
   On Mac/Linux: source venv/bin/activate

3. Install dependencies:  
   pip install -r requirements.txt

4. Run the server:  
   python manage.py runserver

5. Open your browser and go to:  
   http://127.0.0.1:8000/

**Features:**  
- Upload and store music files  
- Organize songs by artist, album, or genre  
- Preview songs using built-in audio player  
- Responsive Bootstrap interface  
- Admin dashboard for managing content

**Troubleshooting:**  
- Ensure `media/` folder exists and is writable  
- Check `settings.py` for correct `MEDIA_ROOT` and `MEDIA_URL`  
- Use `python manage.py collectstatic` if deploying to production  
- Confirm audio formats are supported by your browser

**Author:**  
Chintala Jayaram Bhavani Prasad  
GitHub: https://github.com/Jayaram4210



