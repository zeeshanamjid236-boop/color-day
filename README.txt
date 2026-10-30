COLOR DAY WEBSITE - COMPLETE SETUP (Roman Urdu)

ZIP KE ANDAR:
1) index.html  - Website ki complete coding
2) supabase-setup.sql - Database table aur public policies
3) README.txt - Ye setup guide

PART 1 - SUPABASE DATABASE
1. https://supabase.com par login karein.
2. Apna Supabase project open karein.
3. Left menu mein SQL Editor kholein.
4. New query par click karein.
5. supabase-setup.sql file open karein, sara SQL copy karke SQL Editor mein paste karein.
6. Run button dabayein. Table aur policies create ho jayengi.

PART 2 - SUPABASE KE URL AUR KEY
1. Supabase project mein Project Settings kholein.
2. API Keys section (ya Connect/API settings) kholein.
3. Project URL copy karein.
4. Publishable key copy karein (aksar sb_publishable_ se shuru hoti hai).
5. ZIP se index.html ko Notepad mein open karein.
6. Ctrl+F dabayein aur SUPABASE_URL search karein.
7. Is line mein apna URL quotes ke andar paste karein:
   const SUPABASE_URL = "PASTE_YOUR_SUPABASE_PROJECT_URL_HERE";
8. SUPABASE_KEY wali line mein publishable key quotes ke andar paste karein:
   const SUPABASE_KEY = "PASTE_YOUR_SUPABASE_PUBLISHABLE_KEY_HERE";
9. Ctrl+S se save karein.

IMPORTANT SECURITY:
- Sirf Publishable key (ya legacy anon/public key) browser wali website mein use karein.
- service_role key ya Secret key kabhi HTML/GitHub par paste na karein.
- Login nahi hai; is setup mein public visitors wishes read aur add kar sakte hain.
- Public content mein personal/sensitive information na likhein. Spam ya misuse ho sakta hai.

PART 3 - GITHUB PAGES PAR WEBSITE PUBLISH
1. GitHub par apni website wali repository open karein.
2. Add file > Upload files par click karein.
3. Is ZIP ko pehle apne computer par Extract karein.
4. Extracted folder ke andar se index.html upload karein (ZIP ko direct upload na karein).
5. Agar index.html pehle se hai to usay replace/overwrite karein.
6. Commit changes dabayein.
7. Repository > Settings > Pages mein check karein:
   Deploy from a branch / main / /(root)
8. 1-3 minutes baad apna GitHub Pages link refresh karein.

PART 4 - TEST
1. Website open karein.
2. Name aur wish likh kar Share My Wish dabayein.
3. Wish neeche list mein dikhni chahiye.
4. Website ko refresh karein. Wish phir bhi honi chahiye.
5. Website link kisi doosre phone par khol kar bhi check karein.

AGAR ERROR AAYE
- "Pehle Supabase URL..." ka matlab URL/key abhi placeholders hain.
- Wishes load/save error aaye to SQL dobara check karein, table ka naam color_day_wishes hona chahiye.
- Browser mein hard refresh karein: Ctrl + F5.

NOTE:
Wishes Supabase cloud database mein save hoti hain, sirf browser mein nahi.
Ye public no-login website hai, is liye har visitor wishes dekh aur add kar sakta hai.
