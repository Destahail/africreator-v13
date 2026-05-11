# AfriCreator IQ V13 Fixed Full Project

This version removes lucide-react completely to avoid missing export build errors.

## Deploy order
1. Supabase
2. Render backend
3. Vercel frontend

## Supabase
Run: database/v13_schema.sql

## Render backend
Root Directory: backend
Build Command: npm install
Start Command: npm start
Environment variables: SUPABASE_URL, SUPABASE_SERVICE_ROLE_KEY

## Vercel frontend
Root Directory: frontend
Framework: Vite
Build Command: npm run build
Output Directory: dist
Environment variables: VITE_API_URL, VITE_SUPABASE_URL, VITE_SUPABASE_ANON_KEY
