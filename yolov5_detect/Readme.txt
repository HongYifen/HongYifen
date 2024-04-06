detect加载模型参数best.pt后，打开摄像头进行识别，识别结果将会保存在runs文件夹的exp下，结果会覆盖。
需要按照requirements配环境，由于torch打包时出问题，并没有将程序打包出来。
结果说明：分为四类：黑麻疹病，黑腐病，叶斑病，健康。'black_measles', 'black_root', 'blight', 'healthy'