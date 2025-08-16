# AI Resume Screener (Next.js)

A Next.js (App Router) application for AI-powered resume screening, skill extraction, job recommendations, and reporting.

## Quick Start
```bash
# install deps
npm install

# dev server
npm run dev

# build + start
npm run build
npm run start
```

## Environment
Copy `.env.example` to `.env.local` and fill the values detected from the code.
Keys found: (none detected).

## Docker
```bash
docker build -t ai-resume-screener .
docker run -p 3000:3000 --env-file .env.local ai-resume-screener
```

## Project Tree
# AI Resume Screener

This repository contains an AI-powered resume screening application.

## Quick start
```bash
pip install -r requirements.txt
./run.sh
```

## Structure
    .gitignore  (313 bytes)
app/api/ai-recommendations/route.ts  (6821 bytes)
app/api/analyze-skills/route.ts  (4671 bytes)
app/api/auth/login/route.ts  (936 bytes)
app/api/auth/register/route.ts  (1150 bytes)
app/api/extract-text/route.ts  (4406 bytes)
app/api/generate-report/route.ts  (1848 bytes)
app/api/job-recommendations/route.ts  (10786 bytes)
app/auth/login/page.tsx  (5108 bytes)
app/auth/register/page.tsx  (7830 bytes)
app/dashboard/page.tsx  (269 bytes)
app/globals.css  (124 bytes)
app/layout.tsx  (475 bytes)
app/page.tsx  (1268 bytes)
components/ai-recommendations.tsx  (7115 bytes)
components/circular-progress.tsx  (1969 bytes)
components/dashboard-layout.tsx  (7592 bytes)
components/file-upload.tsx  (2573 bytes)
components/protected-route.tsx  (773 bytes)
components/skill-analysis.tsx  (5307 bytes)
components/tabs/ats-analysis-tab.tsx  (14329 bytes)
components/tabs/job-recommendations-tab.tsx  (21852 bytes)
components/tabs/personal-guidance-tab.tsx  (16816 bytes)
components/tabs/profile-tab.tsx  (11831 bytes)
components/tabs/resume-analysis-tab.tsx  (15393 bytes)
components/theme-provider.tsx  (292 bytes)
components/ui/accordion.tsx  (1991 bytes)
components/ui/alert-dialog.tsx  (4434 bytes)
components/ui/alert.tsx  (1232 bytes)
components/ui/aspect-ratio.tsx  (154 bytes)
components/ui/avatar.tsx  (1369 bytes)
components/ui/badge.tsx  (1088 bytes)
components/ui/breadcrumb.tsx  (2712 bytes)
components/ui/button.tsx  (1901 bytes)
components/ui/calendar.tsx  (7648 bytes)
components/ui/card.tsx  (1858 bytes)
components/ui/carousel.tsx  (6224 bytes)
components/ui/chart.tsx  (10480 bytes)
components/ui/checkbox.tsx  (1070 bytes)
components/ui/collapsible.tsx  (329 bytes)
components/ui/command.tsx  (4899 bytes)
components/ui/context-menu.tsx  (7260 bytes)
components/ui/dialog.tsx  (3849 bytes)
components/ui/drawer.tsx  (3021 bytes)
components/ui/dropdown-menu.tsx  (7433 bytes)
components/ui/form.tsx  (4099 bytes)
components/ui/hover-card.tsx  (1198 bytes)
components/ui/input-otp.tsx  (2168 bytes)
components/ui/input.tsx  (791 bytes)
components/ui/label.tsx  (724 bytes)
components/ui/menubar.tsx  (7988 bytes)
components/ui/navigation-menu.tsx  (5046 bytes)
components/ui/pagination.tsx  (2751 bytes)
components/ui/popover.tsx  (1244 bytes)
components/ui/progress.tsx  (773 bytes)
components/ui/radio-group.tsx  (1481 bytes)
components/ui/resizable.tsx  (1723 bytes)
components/ui/scroll-area.tsx  (1656 bytes)
components/ui/select.tsx  (5567 bytes)
components/ui/separator.tsx  (770 bytes)
components/ui/sheet.tsx  (4281 bytes)
components/ui/sidebar.tsx  (23381 bytes)
components/ui/skeleton.tsx  (261 bytes)
components/ui/slider.tsx  (1091 bytes)
components/ui/sonner.tsx  (894 bytes)
components/ui/switch.tsx  (1153 bytes)
components/ui/table.tsx  (2765 bytes)
components/ui/tabs.tsx  (1900 bytes)
components/ui/textarea.tsx  (745 bytes)
components/ui/toast.tsx  (4770 bytes)
components/ui/toaster.tsx  (786 bytes)
components/ui/toggle-group.tsx  (1753 bytes)
components/ui/toggle.tsx  (1541 bytes)
components/ui/tooltip.tsx  (1159 bytes)
components/ui/use-mobile.tsx  (565 bytes)
components/ui/use-toast.ts  (3948 bytes)
components.json  (443 bytes)
hooks/use-auth.ts  (1373 bytes)
hooks/use-mobile.tsx  (565 bytes)
hooks/use-toast.ts  (3948 bytes)
lib/utils.ts  (166 bytes)
next.config.mjs  (228 bytes)
package.json  (2221 bytes)
pnpm-lock.yaml  (92 bytes)
postcss.config.mjs  (135 bytes)
public/placeholder-logo.png  (568 bytes)
public/placeholder-logo.svg  (3208 bytes)
public/placeholder-user.jpg  (1635 bytes)
public/placeholder.jpg  (1064 bytes)
public/placeholder.svg  (3253 bytes)
requirements.txt  (0 bytes)
styles/globals.css  (2373 bytes)
tailwind.config.ts  (2634 bytes)
tsconfig.json  (595 bytes)

