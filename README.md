# TableViewHeaderStretching

##快速集成可拉伸头部图片的UITableView

1、新建一个UITableViewController继承自HeaderStretchingTableViewController

2、设置导航栏的背景图片
  self.navigation_backgroundImageName = @"navigation_background";
  
3、设置被拉伸图片view的高度
    self.stretchingImageHeight = 200;
    
4、设置头部拉伸图片的名称
    self.stretchingImageName = @"image_bg";
