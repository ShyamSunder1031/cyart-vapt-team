git clone https://github.com/ShyamSunder1031/cyart-vapt-team.git
cd cyart-vapt-team
mkdir -p Week3/Recon Week3/Scanning Week3/Exploitation Week3/Post-Exploitation Week3/Screenshots

touch Week3/Recon/.gitkeep
touch Week3/Scanning/.gitkeep
touch Week3/Exploitation/.gitkeep
touch Week3/Post-Exploitation/.gitkeep
touch Week3/Screenshots/.gitkeep
cat > Week3/README.md << 'EOF'
# Week 3 - VAPT Report

## Scope
## Tools Used
## Findings Summary
EOF
git add .
git commit -m "Add Week3 VAPT folder structure"
git push origin main
```

---

That's it! Your repo will then look like:
```
cyart-vapt-team/
   |-- Week2/
   |-- Week3/
   |-- README.md
   |-- Shyam Sunder VAPT Task 03.pdf
