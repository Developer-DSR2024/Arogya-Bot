# 🗄️ Supabase Database

## Project Info
| | |
|---|---|
| Platform | Supabase (supabase.com) |
| Database | PostgreSQL |
| Project URL | https://nqhjdhrilrdkzltbkytq.supabase.co |
| Tables | consultations, reminders |

---

## 📋 Table: consultations
| Column | Type | Description |
|---|---|---|
| id | uuid | Unique ID (auto-generated) |
| user_id | text | Anonymous user identifier |
| symptoms | text | What the user typed |
| ai_response | text | AI's reply |
| severity | text | LOW / MEDIUM / HIGH |
| language | text | en or hi |
| created_at | timestamp | When saved |

## 💊 Table: reminders
| Column | Type | Description |
|---|---|---|
| id | uuid | Unique ID (auto-generated) |
| user_id | text | Anonymous user identifier |
| medicine_name | text | Name of medicine |
| dosage | text | How much to take |
| frequency | text | How often |
| time | text | What time |
| duration | text | How many days |
| created_at | timestamp | When saved |

---

## 👀 How to View Live Data (For Demo)
1. Go to **supabase.com** → ArogyaBot project
2. Click **"Table Editor"** in left sidebar
3. Click **"consultations"** or **"reminders"**
4. Show judges real-time data appearing! 🔥

## 🧪 Test the Connection
1. Open **SupabaseTest.html** in Chrome
2. Should show **"✅ Connected to Supabase!"**
3. Click **"Insert Sample Consultations"** → **"Read All Data"**
