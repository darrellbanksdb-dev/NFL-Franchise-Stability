library(ggplot2)

p_quad <- ggplot(team_summary, aes(x = avg_stability, y = avg_wins)) +
  
  geom_point(size = 4, color = "#2C7FB8") +
  
  geom_text(aes(label = Tm), vjust = -0.8, size = 3.5) +
  
  geom_vline(xintercept = avg_stability_league, linetype = "dashed") +
  
  geom_hline(yintercept = avg_wins_league, linetype = "dashed") +
  
  labs(
    title = "NFL Franchise Stability vs Performance (2016–2025)",
    subtitle = "Comparing average wins with leadership stability",
    x = "Average Stability Index (Coach + QB Tenure)",
    y = "Average Wins"
  ) +
  
  theme_minimal()

p_quad
