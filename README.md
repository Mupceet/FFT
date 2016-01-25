# FFT
来源：http://sourceforge.net/projects/kissfft/

接口：
FFTWithWindow(double *data, int data_len, WindowType win, int win_len)
FFTWithWindowWithPhase(double *data, int data_len, WindowType win, int win_len)

变换后返回的数据，一是实部虚部表示的复数，一是模加相位表示的复数。
