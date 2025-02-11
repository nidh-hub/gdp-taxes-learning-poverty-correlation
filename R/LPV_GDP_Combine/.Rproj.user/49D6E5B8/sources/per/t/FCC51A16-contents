cols = colnames(df)
for(i in 1:length(df$year)) {
  if(df$year[i] %in% cols) {
    df$gdp[i]<-df[[which(cols %in% df$year[i])]][i]
  }
}
  