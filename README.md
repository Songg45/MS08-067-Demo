# MS08-067-Test
Credit to http://www.phreedom.org/blog/2008/decompiling-ms08-067/ . This repo has one change from the original to allow the code be ran on Visual Studios 2019 by changing main to the following:

    int main()
    {
        wchar_t name[] = L"\\c\\..\\..\\AAAAAAAAAAAAAAAAAAAAAAAAAAAAA";

        return ms08_067(name);
    }
