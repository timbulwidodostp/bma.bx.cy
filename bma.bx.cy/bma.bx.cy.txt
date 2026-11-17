# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Bayesian Mediation Analysis Use bma.bx.cy (BayesianMediationA) With (In) R Software
install.packages("BayesianMediationA")
library("BayesianMediationA")
# Estimate Bayesian Mediation Analysis Use bma.bx.cy (BayesianMediationA) With (In) R Software
bma.bx.cy = read.csv("https://raw.githubusercontent.com/timbulwidodostp/bma.bx.cy/main/bma.bx.cy/bma.bx.cy.csv",sep = ";")
bma.bx.cy <- bma.bx.cy(pred = bma.bx.cy[,3], m = bma.bx.cy[,c(14, 12, 13)], y = bma.bx.cy[,1], n.iter = 500, n.burnin = 100)
summary(bma.bx.cy)
# Bayesian Mediation Analysis Use bma.bx.cy (BayesianMediationA) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished