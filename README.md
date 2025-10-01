# RefID - Identify Refrigerants in Unknown Bottles

RefID is a web tool that helps you determine refrigerants based on temperature and pressure data. It works with a database of P-T data for temps in 1 degree increments.

---

## **How to Use RefID**

### 1. **Select Temperature & Pressure**
- Enter the **temperature** and **pressure** of the refrigerant bottle.
- Choose the **phase** (Bubble or Dew), **pressure type** (Gauge/Absolute), and units for both temperature and pressure.

### 2. **Lookup Lists**
- **Lookup List:** Your personal selection of refrigerants for comparison.  
  - Use **Reset defaults** to restore the common refrigerants.  
  - Use **Save lookup list** to store your custom list in the browser.
- **All Refrigerants:** Full list of refrigerants available to add to your lookup list. 

### 4. **Find Matches**
- Click **Find matches** to see the table of refrigerants ranked by how closely their pressure matches your input.  
- **Sorting:** Choose to sort by Δ % or Δ absolute.

### 5. **Mobile Experience**
- On mobile devices, the lists and table adapt to the screen for easier use.  
- The table automatically scrolls into view after clicking **Find matches**.

### 6. **Disclaimer**
Use the results as a guide. This tool is **provided "as-is"**. Always verify with technical references — results are not a substitute for professional advice.

---

## **Development & Deployment**

- The project is managed with **GitHub** for version control.
- Deployed via **Cloudflare Pages**.
- To update the site:
  1. Make changes locally.
  2. Commit and push to the GitHub repository.
  3. Cloudflare Pages will automatically rebuild and deploy the site.

---

## **Links**
- [Live Site](https://refid.net)  
- [Cloudflare Pages Documentation](https://developers.cloudflare.com/pages)  
- [GitHub Repository](https://github.com/oliemery311/refid)
