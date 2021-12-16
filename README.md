# STM32_DataBusMaster
```
установить плагины vscode:
Cortex-Debug
Makefile Tools
windows-arm-none-eabi

скачать дополнительные файлы и прописать переменные:
install OpenOCD - сервер для взаимодействия с программатором; пример переменной среды (C:\xpack-openocd-0.11.0-3\bin)
install gcc-arm-none-eabi-10.3-2021.10 - компилятор; пример переменной среды (C:\gcc-arm-none-eabi-10.3-2021.10\bin)
install xpack-windows-build-tools-4.2.1-2 - мэйк; пример переменной среды (C:\xpack-openocd-0.11.0-3\bin)
install en.stm32f1_svd - конфигурации прогромматора
ссылки:
https://github.com/xpack-dev-tools/windows-build-tools-xpack/releases
https://github.com/xpack-dev-tools/openocd-xpack/releases
https://github.com/xpack-dev-tools/arm-none-eabi-gcc-xpack/releases/
https://www.st.com/en/microcontrollers-microprocessors/stm32f1-series.html#cad-resources

дополнительные ссылки:
https://mynewt.apache.org/latest/get_started/native_install/cross_tools.html
https://xpack.github.io/openocd/install/#manual-install

Examples:
https://habr.com/ru/post/585464/
https://forum.pedalpcb.com/threads/setting-up-vscode-openocd-xpack-st-link-for-debugging-on-macos-big-sur.4861/
https://adelectronics.ru/2019/04/22/visual-studio-code-%D0%BD%D0%B0%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B8-%D0%BE%D1%82%D0%BB%D0%B0%D0%B4%D0%BA%D0%B0-%D0%BF%D1%80%D0%BE%D1%88%D0%B8%D0%B2%D0%BE%D0%BA-%D0%B4%D0%BB%D1%8F-arm-co/

заметки:
после добавления переменной среды перезагрузить vscode
