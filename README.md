# 🔍 DefectVision

DefectVision is a motherboard defect detection system that uses **YOLOv11** to find defects on motherboards. It makes quality checking faster and more reliable than manual human inspection.

[Live Demo](https://defect-vision.netlify.app/) · [Video Demonstration](https://youtu.be/PCcpFBIT7W4)

> Thesis project by [your names / team / school and year]

## ✨ Features

- Detects motherboard defects using a YOLOv11 model
- Scan screen for running inspections (`Start Scanning`)
- Results shown in data tables
- [Add anything else: login, history, statistics...]

## 🧰 Tech Stack

- **Web app:** Next.js, TypeScript [confirm: Tailwind CSS, shadcn/ui]
- **Database:** MongoDB
- **Detection:** Python + YOLOv11 (`defect_vision_script.py`), running on a Raspberry Pi
- **Hosting:** Netlify

## 🗂️ Project Structure

| Path | What it is |
| --- | --- |
| `src/` | Web app source code |
| `public/` | Static assets |
| `defect_vision_script.py` | Detection script that runs on the Raspberry Pi |

## 🚀 Getting Started

1. Clone the repo and install dependencies:
```
   npm install
```
2. Create a `.env.local` file in the project root:
```
   MONGODB_URI="your-mongodb-connection-uri-here"
   SESSION_SECRET="your-randomly-generated-session-secret"
```
3. Run the development server:
```
   npm run dev
```
4. Open http://localhost:3000

## 🤖 Detection Script

[Explain how to run `defect_vision_script.py`: required hardware, Python libraries, and the model file.]

## 👥 Team

- [Name] – [role]
- [Name] – [role]