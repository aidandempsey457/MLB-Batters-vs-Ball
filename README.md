# MLB-Batters-vs-Ball
This project analyzes Statcast data to understand how MLB batters perform against different types of pitches, independent of the individual pitchers who throw them.
This data is from the 2025 MLB season to:
- Cluster pitchers using pitch-level metrics
- Analyze batter performance vs. clusters
- Calculate advanced stats like wOBA, wRAA, and WAR
- Output relational Excel files


--

## 📁 Folder Structure

The code will automatically create folders in the same directory as your script:

/data ← Saves pulled Statcast data
/output ← Saves processed Excel files

---

## 📚 Dependencies

This project makes extensive use of [pybaseball](https://github.com/jldbc/pybaseball), an open-source Python package for accessing baseball data including Statcast, PitchFX, and more.

You can install it with:

```bash
pip install pybaseball

---

## 🚀 How to Run

1. Clone the repository
2. Install required packages:
3. pip install -r requirements.txt


---

## 📦 Output

- `data/statcast_2025_through_YYYY-MM-DD.xlsx`: Raw Statcast data
- `output/relational_cluster_2025_YYYY-MM-DD.xlsx`: Processed Excel file with batter/cluster stats

---

## 📘 Notes

- Requires internet connection (for `pybaseball`)
- Works on Windows/macOS/Linux

