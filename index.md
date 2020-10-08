from tkinter import *
window = Tk()
window.title("Read This")
Label (window, text="!!IMPORTANT!!\n\nWelcome to the gmailer, the gmail bot by Ammaar. This is the spamming edition of the gmailer and it only works with gmail. This version can spam 30 emails at once. Before you run the application, read this carefully.\nThere are 2 ways you can spam mails,\n 1. Use you own email id or\n 2. Use the built in email id.\nIf you choose 1, you need to make sure to enable the less secure apps function in gmail. To do this, go to myaccount.google.com/lesssecureapps and toggle the Allow Less Secure Apps on. Now you are ready to rock. Here are some important info:\n -This software is in its early stages and hence some bugs are to be expected.\n -Use this software at your own risk and please use it mindfully. Do not get into trouble for no reason\n -Any suggestions and feedback can be submitted at ammaarmuhammad509@gmail.com\n\nBy closing this window, you agree to the T and c’s <which I am yet to make but you agree anyways> and you promise to use this responsibly\nEnjoy :)\n\n—Ammaar", bg='black', fg='white', font="none 10 bold") .grid(row=0, column=0, sticky=E)
window.mainloop()
print("WELCOME TO THE GMAIL BOT CREATED BY AMMAAR ON 7/10/2020")
input("PRESS ENTER TO CONTINUE...")

x = ("Who do you want to send this to? \n\n")
y = ("Please enter your email subject\n\n")
z = ("Please enter your email body\n\n")
a = ("Please enter your name so that the receiver knows who you are\n\n")
b = ("Please choose:\n1. I want to use my own email\n2. I want to use the built in email\n")

number1 = input(b)


if number1 == str("1"):

    p = input("Enter the email from which you would like to send your message\n\n")
    q = input("Enter the password associated with your email\n\n")
    r = input(x)
    s = input(y)
    t = input(z)
    u = input(a)
    email = r
    subject = s
    content = t
    sender = u
    print("\n\nHold Tight...")

    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("1")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("2")
    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("3")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("4")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("5")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("6")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("7")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("8")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("9")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("10")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("11")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("12")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("13")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("14")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("15")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("16")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("17")
    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("18")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("19")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("20")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("21")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("22")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("23")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("24")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("25")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("26")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("27")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("28")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("29")

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login(p, q)
    finalmessage = str("Subject:" + subject + "\n\n" + content + "\n\n" + sender)
    conn.sendmail(p, r, finalmessage)
    print("30")


else:
    email1 = input(x)
    sub1 = input(y)
    body1 = input(z)
    sender1 = input(a)
    print("\n\nHold Tight...")
    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o)

    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 1)





    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 2)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 3)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 4)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 5)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 6)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 7)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 8)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 9)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 10)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 11)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 12)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 13)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 14)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 15)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o  + 16)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 17)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 18)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 19)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 20)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 21)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 22)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 23)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 24)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 25)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 26)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 27)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 28)






    import smtplib

    conn = smtplib.SMTP('smtp.gmail.com', 587)
    type(conn)
    conn
    conn.ehlo()
    conn.starttls()
    conn.login("themailerbot@gmail.com", "yH6BJP8QzaSs")
    finalmessage = str("Subject:" + sub1 + "\n\n" + body1 + "\n\n" + sender1)
    conn.sendmail("themailerbot@gmail.com", email1, finalmessage)
    o = int("1")
    print(o + 29)













