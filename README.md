# BootstrapBtn
## swift Bootstrap Button
swift bootstrap sytle, swift3 Bootstrap Button. Use Swift3.0 Create a Button like Bootstrap 2016-11-15
## like this Button

![image](https://github.com/zhangliangzhi/BootstrapBtn/raw/master/bootcss_button.png)

# How to use it 
`
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
        
        let cw = self.view.frame.width/2 - 50
        let defaultBtn: BootstrapBtn = BootstrapBtn(frame: CGRect(x:cw, y:140, width:100, height:40), btButtonType: BootstrapBtn.BootstrapBtnType.Default)
        defaultBtn.setTitle("Default", for: UIControlState.normal)
        self.view.addSubview(defaultBtn)
        
        let primaryBtn: BootstrapBtn = BootstrapBtn(frame: CGRect(x:cw, y:190, width:100, height:40), btButtonType: .Primary)
        primaryBtn.setTitle("Primary", for: UIControlState.normal)
        self.view.addSubview(primaryBtn)
        
        let successbtn: BootstrapBtn = BootstrapBtn(frame: CGRect(x:cw, y:240, width:100, height:40), btButtonType: .Success)
        successbtn.setTitle("Success", for: UIControlState.normal)
        self.view.addSubview(successbtn)
        
        let infobtn: BootstrapBtn = BootstrapBtn(frame: CGRect(x:cw, y:290, width:100, height:40), btButtonType: .Info)
        infobtn.setTitle("Info", for: UIControlState.normal)
        self.view.addSubview(infobtn)
        
        let warningbtn: BootstrapBtn = BootstrapBtn(frame: CGRect(x:cw, y:340, width:100, height:40), btButtonType: .Warning)
        warningbtn.setTitle("Warning", for: UIControlState.normal)
        self.view.addSubview(warningbtn)
        
        let dangerbtn: BootstrapBtn = BootstrapBtn(frame: CGRect(x:cw, y:390, width:100, height:40), btButtonType: .Danger)
        dangerbtn.setTitle("Danger", for: UIControlState.normal)
        self.view.addSubview(dangerbtn)
    }
`