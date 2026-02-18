# Tempermeter
Simple and lightweight application to display temperature on the digital screen of AIO cooler.

Download the application [here](https://github.com/MKNETID/Project/raw/refs/heads/Tempermeter/App/Tempermeter.zip)

This app only works on products that use:
'''
VENDOR_ID = 0x5131;
PRODUCT_ID = 0x2007;
'''
example: DA KS240, DA KS360.

If you are using a different product, you can change the Vendor and Product ID accordingly in MainForm.cs.
'''
public partial class MainForm : Form
{
    private const int VENDOR_ID = 0x5131;
    private const int PRODUCT_ID = 0x2007;
'''
