https://github.com/Shayan1191/Shm-13671371/actions- 👋 Hi, I’m @Shayan1191
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Shayan1191/Shayan1191 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import requests

def find_next_amount(current_amount):
    return current_amount * 5

def check_website(url):
  5da02e0e-4c4b-45f4-b261-ba595b85c091    response = requests.get(url)
    if response.status_code == 200:
        print(f"وب‌سایت {url} در دسترس است.")
    else:
        print(f"وب‌سایت {url} در دسترس نیست.")

if __name__ == "__main__":
    entered_amount = float(input"10000: "))
    next_amount = find_next_amount(entered_amount)
    
    if next_amount >= 100000:
        print("شما برنده شدید!")
    elif next_amount < 100000 and next_amount >= entered_amount:
        print(f"شما به مبلغ {next_amount} رسیدید، اما برنده نیستید.")
    else:
        print(f"مبلغ بعدی باید حداقل {next_amount} باشد تا برنده شوید.")
    
    website_url = input("https//:jetbet900.com ")
    check_website(website:url)
