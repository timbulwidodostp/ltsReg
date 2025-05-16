# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Least Trimmed Squares Robust (High Breakdown) Regression Use ltsReg (robustbase) With (In) R Software
install.packages("robustbase")
library("robustbase")
ltsReg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ltsReg/main/ltsReg/ltsReg.csv",sep = ";")
# Estimation Least Trimmed Squares Robust (High Breakdown) Regression Use ltsReg (robustbase) With (In) R Software
ltsReg <- ltsReg(stack.loss ~ Air.Flow + Water.Temp + Acid.Conc., data = ltsReg)
summary(ltsReg)
# Least Trimmed Squares Robust (High Breakdown) Regression Use ltsReg (robustbase) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished