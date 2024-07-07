<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Searchable Links</title>
    <style>
        /* Optional: Basic styling for better presentation */
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        input[type="text"] {
            padding: 8px;
            margin-bottom: 10px;
            width: 300px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin-bottom: 5px;
        }
        a {
            text-decoration: none;
            color: #0366d6; /* Link color */
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Searchable Links</h1>
    <input type="text" id="searchInput" placeholder="Search links...">
    <ul id="linkList">
        <!-- Generating 50 links -->
        <!-- Change the href="#" to actual URLs you want -->
        <!-- You can also change the link text as needed -->
        <!-- Example: Link 1, Link 2, ..., Link 50 -->
        <!-- Adjust the loop index as necessary -->
        <!-- This example generates links numbered from 1 to 50 -->
        <!-- You can modify it to suit your specific needs -->
        <!-- For demonstration, they all link to "#" -->
        <!-- Add your desired URLs and link text -->
        <!-- Link 1 <li><a href="#">Link 1</a></li> -->
        <li><a href="https://drive.google.com/file/d/1nNBVcokoGVzwktZxAYQIdg71PAp9ZQmx/view?usp=sharing">Link 1</a></li>
        <li><a href="https://drive.google.com/file/d/1X5A7mnPy5oQ2uUQeGXgSkw6CpehJnE9N/view?usp=sharing">Link 2</a></li>
        <li><a href="https://drive.google.com/file/d/1icesVlfK_azzfI59toDa5MN0y0mtix9R/view?usp=sharing">Link 3</a></li>
        <li><a href="https://drive.google.com/file/d/1jCLS12Nhly11GGwgH2xhkgCg_JaYuo9o/view?usp=sharing">Link 4</a></li>
        <li><a href="https://drive.google.com/file/d/1cYx2jtvYOL9XCGarXQaxvaC3IPWw7i5_/view?usp=sharing">Link 5</a></li>
        <li><a href="https://drive.google.com/file/d/1fC920q4CcjFtGBnaG7tAxwSdy82f3e0E/view?usp=sharing">Link 6</a></li>
        <li><a href="https://drive.google.com/file/d/1ASeKPvP1a83WVOBgK5EVUEA7dq41B4np/view?usp=sharing">Link 7</a></li>
        <li><a href="https://drive.google.com/file/d/1qnC_nr5L3VG-k5MtifY0RxXhqnhrG3W9/view?usp=sharing">Link 8</a></li>
        <li><a href="https://drive.google.com/file/d/1BObXPaVqlEhX3LNhbNADvZu1LT9qgCLB/view?usp=sharing">Link 9</a></li>
        <li><a href="https://drive.google.com/file/d/1A53hg4k2-tCNwU27rXnzXhFmh5tJ9qIH/view?usp=sharing">Link 10</a></li>
        <li><a href="https://drive.google.com/file/d/1uYt-s5D2pPNEklZZKZqPvL5oO6_pR619/view?usp=sharing">Link 11</a></li>
        <li><a href="https://drive.google.com/file/d/1nSBimWW3Wzge_n5tlmbMv9GJ6D1j0of3/view?usp=sharing">Link 12</a></li>
        <li><a href="https://drive.google.com/file/d/1esnjzw250rwV5oz9QYEIa417mvluELbA/view?usp=sharing">Link 13</a></li>
        <li><a href="https://drive.google.com/file/d/1J62wFrnRLb3Rpg8zp__7IFsr69BQtc_j/view?usp=sharing">Link 14</a></li>
        <li><a href="https://drive.google.com/file/d/1p8gJ90i4j6-DuYIA0P7xaC5KeRiTATUk/view?usp=sharing">Link 15</a></li>
        <li><a href="https://drive.google.com/file/d/1Md_H9pBE6bcHOJd9_juCKRZb4p5D0Lx-/view?usp=sharing">Link 16</a></li>
        <li><a href="https://drive.google.com/file/d/1q_kUYtE_TRrU9or3Q7UuaEnYvh-sLzmD/view?usp=sharing">Link 17</a></li>
        <li><a href="https://drive.google.com/file/d/10LzyIb3rqFjm_fdZNVbCv0ZtRStIX5qv/view?usp=sharing">Link 18</a></li>
        <li><a href="https://drive.google.com/file/d/1przIOwCQpI1lxn_NzOAeFlsEpjudbHga/view?usp=sharing">Link 19</a></li>
        <li><a href="https://drive.google.com/file/d/1Xgo76iIpOdSmRw5TbcMEZoQEFGBjOJbT/view?usp=sharing">Link 20</a></li>
        <li><a href="https://drive.google.com/file/d/1X-Ya82XJ8MUMLx9FyoxKF8Y5-meYei1H/view?usp=sharing">Link 21</a></li>
        <li><a href="https://drive.google.com/file/d/1eXI9dWfSrpXg-EVaIOMAmFgn4aTisYFj/view?usp=sharing">Link 22</a></li>
        <li><a href="https://drive.google.com/file/d/1fya2owL_LGs0BLaLd-yq_WnV8X2N7kxd/view?usp=sharing">Link 23</a></li>
        <li><a href="https://drive.google.com/file/d/1zZHeMNwYjSD2k8BHGpRlG2I4Qn_mayWM/view?usp=sharing">Link 24</a></li>
        <li><a href="https://drive.google.com/file/d/1LXb5ae_c82xP8ff_wv3WoRpeUINEaZRl/view?usp=sharing">Link 25</a></li>
        <li><a href="https://drive.google.com/file/d/1zaV1m1q8ojO1mhB9w6VnEyZ1uZufNHrK/view?usp=sharing">Link 26</a></li>
        <li><a href="https://drive.google.com/file/d/1aeACdDkczCZstmub1mxAXV28XoElAnNG/view?usp=sharing">Link 27</a></li>
        <li><a href="https://drive.google.com/file/d/1DcUYVGNdj2cH9FIEmMr3AWDC3LLv6Eq2/view?usp=sharing">Link 28</a></li>
        <li><a href="https://drive.google.com/file/d/1C8GBsPIVplk17ASyv36DLZku8STpvez1/view?usp=sharing">Link 29</a></li>
        <li><a href="https://drive.google.com/file/d/1N5pyp96cj45bZRnL7W-awognipufs0Wn/view?usp=sharing">Link 30</a></li>
        <li><a href="https://drive.google.com/file/d/1glA2A8laFWLEUftnT-eEQwyUsftyzAFQ/view?usp=sharing">Link 31</a></li>
        <li><a href="https://drive.google.com/file/d/1LjZC8BAtb08ffTA2eNOMyzHOhSdPDnf5/view?usp=sharing">Link 32</a></li>
        <li><a href="https://drive.google.com/file/d/1CS9VFBA_BqiOnajXe80h9Vk-L8r6IdRT/view?usp=sharing">Link 33</a></li>
        <li><a href="https://drive.google.com/file/d/1cgolWtZ3cHQPF0F5qimKseWBxXKacdpl/view?usp=sharing">Link 34</a></li>
        <li><a href="https://drive.google.com/file/d/1VfA5XlspmGr5xY83vBefdxA1SRPGswhW/view?usp=sharing">Link 35</a></li>
        <li><a href="https://drive.google.com/file/d/1Mt6HuaLH3Ey4twIRToxWQEpJ3cJj4JwN/view?usp=sharing">Link 36</a></li>
        <li><a href="https://drive.google.com/file/d/1YtbAO4VrTJrWtBhGHEjCSDEnkFtIWLEE/view?usp=sharing">Link 37</a></li>
        <li><a href="https://drive.google.com/file/d/1X5A7mnPy5oQ2uUQeGXgSkw6CpehJnE9N/view?usp=sharing">Link 38</a></li>
        <li><a href="https://drive.google.com/file/d/1y1TREZOgOZQXgFejdgwV2GXfipfaojKx/view?usp=sharing">Link 39</a></li>
        <li><a href="https://drive.google.com/file/d/1pfzNEv3NOc-0FoBdmJalcxv4xqctaC_y/view?usp=sharing">Link 40</a></li>
        <li><a href="https://drive.google.com/file/d/1gHB0v5gSZB4qf--x8UUiE3g9hSbUJeLQ/view?usp=sharing">Link 41</a></li>
        <li><a href="https://drive.google.com/file/d/16m1vOADEBl0_O9Pu8PkvC2-R-E1wkyP-/view?usp=sharing">Link 42</a></li>
        <li><a href="https://drive.google.com/file/d/1dHwvvKxlGgXA9lkjKN5R3-2wblhPi4Id/view?usp=sharing">Link 43</a></li>
        <li><a href="https://drive.google.com/file/d/1mt5oJiDOUo9LyfWSUq9BYIQelkSPBOo-/view?usp=sharing">Link 44</a></li>
        <li><a href="https://drive.google.com/file/d/1_d4eNhd8y4L9Lmr_QBUsOpzek-CllfQL/view?usp=sharing">Link 45</a></li>
        <li><a href="https://drive.google.com/file/d/1I-odpa4MlWBRcQ0u9gdbcoUXRLxzB4Z8/view?usp=sharing">Link 46</a></li>
        <li><a href="https://drive.google.com/file/d/12nRuNJVLPsVCjxtF1iWRgnMDDrvl5c1p/view?usp=sharing">Link 47</a></li>
        <li><a href="https://drive.google.com/file/d/1FYD1DCEfukGNb1K15SDdUQX9ZI8qeSzG/view?usp=sharing">Link 48</a></li>
        <li><a href="https://drive.google.com/file/d/1firHpnepFxsS17X0svWcLS-0j4Uw9rL1/view?usp=sharing">Link 49</a></li>
        <li><a href="https://drive.google.com/file/d/1qIlJuNV6MeqkMbMwXNBrkhWa95XhOsOl/view?usp=sharing">Link 50</a></li>
    </ul>

    <script>
        // JavaScript to handle the search functionality
        const searchInput = document.getElementById('searchInput');
        const linkList = document.getElementById('linkList').getElementsByTagName('li');

        searchInput.addEventListener('input', function() {
            const searchTerm = this.value.toLowerCase();
            for (let i = 0; i < linkList.length; i++) {
                const linkText = linkList[i].innerText.toLowerCase();
                if (linkText.includes(searchTerm)) {
                    linkList[i].style.display = 'block';
                } else {
                    linkList[i].style.display = 'none';
                }
            }
        });
    </script>
</body>
</html>
