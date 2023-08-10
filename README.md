               await pageName.goto(url);
                        await pageName.waitForNetworkIdle();

                    }

                    // #3 PAGE ACTIONS

                    async function clickFunction(selectorUrl, openedPageToClick) {
                        const clickSelector = selectorUrl;
                        const xPathToClick = await openedPageToClick.waitForXPath(clickSelector);
                        await xPathToClick.click();
                        await new Promise(resolve => setTimeout(resolve, 500));
                            await Promise.waitForNetworkIdle;
                            
                    }

                    async function clickFunctionSelector(selectorUrl, openedPageToClick) {
                        const clickSelector = selectorUrl;
                        await openedPageToClick.waitForSelector(selectorUrl);
                        await openedPageToClick.click(clickSelector);
                        await new Promise(resolve => setTimeout(resolve, 500));
                            await Promise.waitForNetworkIdle;
                    }

                    async function pageActions(url, [elementSelector1, elementSelector2, elementSelector3, elementSelector4, elementSelector5, elementSelector6, elementSelector7, elementSelector8, elementSelector9, elementSelector10, elementSelector11, elementSelector12, elementSelector13,],) {
                        const page4 = await browser.newPage();
                        await page4.goto(url);

                        await page4.waitForNetworkIdle();
                        await page4.waitForSelector(elementSelector1);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector1);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector2);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector2);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector3);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector3);
                        await page4.waitForNetworkIdle();

                        await page4.waitForNetworkIdle();
                        await page4.waitForSelector(elementSelector4);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector4);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector5);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector5);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector6);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector6);
                        await page4.waitForNetworkIdle();
                        
                        await page4.waitForNetworkIdle();
                        await page4.waitForSelector(elementSelector7);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector7);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector8);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector8);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector9);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector9);
                        await page4.waitForNetworkIdle();

                        await page4.waitForNetworkIdle();
                        await page4.waitForSelector(elementSelector10);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector10);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector11);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector11);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector12);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector12);
                        await page4.waitForNetworkIdle();

                        await page4.waitForSelector(elementSelector13);
                        await page4.waitForNetworkIdle();
                        await page4.click(elementSelector13);
                        await page4.waitForNetworkIdle();
                    }

                    // #4 ADD NETWORK 
