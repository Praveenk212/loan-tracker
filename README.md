# 💰 Loan Repayment Tracker

A personal loan dashboard tracking your 4 active loans with the **Avalanche Strategy** — target: debt-free by **March 2028**.

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1 — Create a new GitHub repository

1. Go to [github.com](https://github.com) → click **New repository**
1. Name it: `loan-tracker` (or anything you like)
1. Set to **Public** *(required for free GitHub Pages)*
1. Click **Create repository**

### Step 2 — Upload the file

1. In your new repo, click **Add file → Upload files**
1. Upload `index.html`
1. Click **Commit changes**

### Step 3 — Enable GitHub Pages

1. Go to **Settings** → scroll to **Pages** (left sidebar)
1. Under **Source**, select **Deploy from a branch**
1. Branch: `main` · Folder: `/ (root)`
1. Click **Save**

### Step 4 — Your site is live!

After ~2 minutes, your tracker is live at:

```
https://YOUR-USERNAME.github.io/loan-tracker/
```

-----

## 📱 Features

|Feature |Details |
|-----------------------|---------------------------------------------------------------------------|
|**4 Loan Cards** |Live balance, progress bar, monthly interest cost, total interest remaining|
|**Log Payments** |Record EMI / Extra / Lump Sum payments |
|**Auto Balance Update**|Balance reduces instantly when you log a payment |
|**Payment History** |Full transaction log with filter by loan |
|**Delete & Undo** |Delete a payment → balance is restored |
|**Persistent Storage** |All data saved in browser `localStorage` — survives page refresh |
|**Budget Panel** |Income · EMIs · Expenses · Surplus calculated live |
|**Lump Sum Schedule** |Mar / May / Oct / Nov 2026 injections shown |
|**Timeline** |4-phase repayment roadmap |

-----

## 💡 How to Use

1. **Each month** → log your EMI payments for all 4 loans
1. **When you make extra payments** → log as “Extra Payment”
1. **When you get your lump sums** → log as “Lump Sum”
1. The balance on each card updates automatically
1. The interest remaining recalculates based on new balance

-----

## 🎯 Your Loan Summary

|Loan |Balance |EMI |Rate |Priority |
|---------------------------|---------|-------|------|---------------|
|Personal Loan 2 (HDFC 4343)|₹4,61,302|₹10,900|10.9% |#1 — Attack Now|
|Personal Loan 1 (HDFC 5795)|₹9,86,635|₹39,500|10.8% |#2 |
|Consumer Loan (HDFC 5465) |₹3,01,178|₹9,500 |10.08%|#3 |
|Vehicle Loan (SBI 3161) |₹2,70,000|₹10,500|8.5% |#4 — Last |

-----

## ⚠️ Note on Data Storage

Data is stored in your **browser’s localStorage**. This means:

- ✅ Data persists across page refreshes
- ✅ Works completely offline
- ⚠️ Data is per-device/per-browser (not synced across devices)
- ⚠️ Clearing browser data will reset it

For multi-device sync, consider exporting data manually or hosting with a backend.
