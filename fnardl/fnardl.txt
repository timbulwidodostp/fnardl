# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fourier Nonlinear ARDL (Autoregressive Distributed Lag)(Asymmetric Effects) (FNARDL) Use fnardl (fqardl) With (In) R Software
install.packages("fqardl")
library("fqardl")
# Estimation Fourier Nonlinear ARDL (Autoregressive Distributed Lag)(Asymmetric Effects) (FNARDL) Use fnardl (fqardl) With (In) R Software
fnardl = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fnardl/main/fnardl/fnardl.csv",sep = ";")
fnardl <- fnardl( formula = inv ~ inc, data = fnardl, decompose = c("inc"), max_k = 3, max_p = 4, max_q = 4)
summary(fnardl)
# Fourier Nonlinear ARDL (Autoregressive Distributed Lag)(Asymmetric Effects) (FNARDL) Use fnardl (fqardl) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished