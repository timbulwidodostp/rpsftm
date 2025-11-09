# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Rank-preserving structural failure time models for survival data Use rpsftm With R Software
install.packages("rpsftm")
library("rpsftm")
rpsftm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/rpsftm/main/rpsftm/rpsftm.csv",sep = ";")
# Estimation Rank-preserving structural failure time models for survival data Use rpsftm With R Software
rpsftm <- rpsftm(Surv(progyrs, prog)~rand(imm,1-xoyrs/progyrs), rpsftm, censyrs)
rpsftm
# Rank-preserving structural failure time models for survival data Use rpsftm With R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished