### 调整
在 plot_visual_cost 函数里,由于contour level设置的不合理，导致等高线显示不出来，改为
levels = np.linspace(np.min(J_vals), np.max(J_vals), 21)