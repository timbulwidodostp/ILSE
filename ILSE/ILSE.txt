# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Linear regression based on Iterative Least Square Estimation (ILSE) for missing data Use ilse With (In) R software
install.packages("ILSE")
library("ILSE")
ILSE = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ILSE/main/ILSE/ILSE.csv",sep = ";")
# Estimation Linear regression based on Iterative Least Square Estimation (ILSE) for missing data Use ilse With (In) R software
ILSE <- ilse(Dependen ~ Independen_1 + Independen_2 + Independen_3, data=ILSE)
summary(ILSE)
# Linear regression based on Iterative Least Square Estimation (ILSE) for missing data Use ilse With (In) R software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished