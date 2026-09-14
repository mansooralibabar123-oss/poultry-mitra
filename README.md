# Poultry Mitra — Full Local Prototype

## Included
- Real local user registration/login with salted scrypt password hashes
- SQLite database
- User account dashboard
- Investment request ledger
- Deposit/withdrawal request ledger (demo; no money is moved)
- Admin panel
- Poultry project creation
- Poultry purchase/feed/vaccination/expense/sale records
- Transaction review
- Mobile-friendly UI

## Run
1. Install Python 3.10+.
2. In this folder run: `pip install -r requirements.txt`
3. Set a strong secret: `SECRET_KEY='replace-with-a-long-random-secret'`
4. Run: `python app.py`
5. Open `http://127.0.0.1:5000`

Demo admin:
- Email: `admin@poultrymitra.local`
- Password: `ChangeMe123!`
Change this immediately before any real deployment.

## Production work still required
- HTTPS, secure production secret, CSRF protection, rate limiting and security headers
- PostgreSQL or managed database, backups and audit logging
- KYC/AML workflow and privacy/terms documents
- Integration with a legally approved payment provider (credentials and merchant account required)
- Server-side double-entry ledger and reconciliation
- Regulatory/legal review before accepting public investment or deposits
- Accountant/auditor workflow for poultry purchases, sales, expenses and distributable profit
- Do not advertise guaranteed or fixed returns
