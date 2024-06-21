# p_class-6

{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/chlalszxc/pythonclass/blob/main/ch6.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "BmREGkGw1xB3",
        "outputId": "502d68ab-5afa-4568-efe4-f07fd2a8aaa9"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "test\n",
            "test\n"
          ]
        }
      ],
      "source": [
        "x = input()\n",
        "print(x)"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "str = input(\"How old are you:\")\n",
        "print(str,'years old')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "fzXnpVzT33Ti",
        "outputId": "07f097ab-aa5d-48b2-d51a-bf807b2afa51"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "How old are you:19\n",
            "19 years old\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "x = int(input('number:'))\n",
        "print(x)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "i1GhqKrx4AnU",
        "outputId": "89c0fb4c-1868-4586-c60e-a5bc932edae3"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "number:123\n",
            "123\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "x = float(input('number:'))\n",
        "print(x)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "XIqDUCtl4HFZ",
        "outputId": "16e6ec0f-f265-4dc3-9ad7-b2395bda7ba6"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "number:1.23\n",
            "1.23\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "year = input (\"This year: \")\n",
        "print(year)\n",
        "year = eval(year)\n",
        "year+=1\n",
        "print(\"Next year: \", year)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "fKp_MkQj4LGk",
        "outputId": "6636bf7c-9e54-4a86-9b2d-71dc1b9f2746"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "This year: 2024\n",
            "2024\n",
            "Next year:  2025\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "i = 0\n",
        "result = 0\n",
        "while i < 5:\n",
        "  a =  input(\"성적 입력 : \")\n",
        "  result += int(a)\n",
        "  i += 1\n",
        "\n",
        "print(f'평균 : {result / 5}')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "UKMpMs2q5LWe",
        "outputId": "f5310aee-e75d-4f57-c8dc-7dfd42ad8a33"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "성적 입력 : 10\n",
            "성적 입력 : 30\n",
            "성적 입력 : 100\n",
            "성적 입력 : 50\n",
            "성적 입력 : 66\n",
            "평균 : 51.2\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "test_list = ['one', 'two', 'three']\n",
        "for i in test_list:\n",
        "  print(i)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "SAYGD3Bc5WNX",
        "outputId": "7d1163c4-4169-41c0-a607-e353cc08efbb"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "one\n",
            "two\n",
            "three\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for i in range(10):\n",
        "  print(i)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "rQ4jspOA5YRc",
        "outputId": "4f7b345c-4eb2-4f27-bbeb-edfc39e81b02"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0\n",
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n",
            "7\n",
            "8\n",
            "9\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "result = 0\n",
        "for a in range(1,101):\n",
        "  result += a\n",
        "\n",
        "print(result)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "mWDXe2k85qA5",
        "outputId": "be0a2cf6-28d9-4c4c-8838-de590030fa65"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "5050\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "index = 0\n",
        "s = \"BlockDMask\"\n",
        "for a in s :\n",
        "  if a == 'k':\n",
        "    break\n",
        "\n",
        "  index+=1\n",
        "\n",
        "print(index)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "VapgCkYF5aUt",
        "outputId": "1c4743cd-5eb8-4d74-8169-44a212c33526"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "4\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "result = 0\n",
        "for a in range(1,101):\n",
        "  result += a\n",
        "\n",
        "  if result > 100:\n",
        "    print(a)\n",
        "    break"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0wWw8Rw969Wb",
        "outputId": "443932a4-20a3-4407-c19d-9a3ffa67de33"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "14\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "student = [180, 170, 164, 199, 182, 172, 177]\n",
        "for a in student:\n",
        "  if a>170:\n",
        "    continue\n",
        "  print(a)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "hOF5hHnr6-UY",
        "outputId": "87ece8dd-7ace-458c-92fb-a3668918e936"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "170\n",
            "164\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "result = 0\n",
        "for a in range(1,101):\n",
        "  if a % 2 == 1:\n",
        "    result += a\n",
        "\n",
        "print(result)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "KdgfdW4y7AWu",
        "outputId": "d9a6ebad-7d7d-49c0-85ff-141452f40a5d"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "2500\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = ['Alice','Bob','Charlie']\n",
        "\n",
        "for name in a:\n",
        "  print(name)\n",
        "else:\n",
        "  print('!!FINISH!!')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "sh3WmbNH7B7p",
        "outputId": "cc78a42f-8b90-4e2b-dcc1-d67ab4ee21a2"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Alice\n",
            "Bob\n",
            "Charlie\n",
            "!!FINISH!!\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = ['Alice','Bob','Charlie']\n",
        "\n",
        "for name in a:\n",
        "  if name == 'Bob':\n",
        "    print('!!BREAK!!')\n",
        "    break\n",
        "  print(name)\n",
        "else:\n",
        "  print('!!FINISH!!')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "4MR9BGlv7CXN",
        "outputId": "0b1c2d66-e930-4877-97ce-2fcd1e3e8d1b"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Alice\n",
            "!!BREAK!!\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "sr = ['father', 'mother', 'brother']\n",
        "cnt = 0\n",
        "for s in sr:\n",
        "  for c in s:\n",
        "    if c == 'r':\n",
        "      cnt += 1\n",
        "\n",
        "print(cnt)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ZCNTOt277FO5",
        "outputId": "ddd75855-85cd-404f-e543-5f1b02ef6e40"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "4\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = []\n",
        "for i in range(10):\n",
        "  a.append(0)\n",
        "\n",
        "print(a)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "eFEeJt-_7Gqt",
        "outputId": "cfedbf5a-1f34-45b6-8f76-0b5ddf622f67"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[0, 0, 0, 0, 0, 0, 0, 0, 0, 0]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = []\n",
        "\n",
        "for i in range(3):\n",
        "  line = []\n",
        "  for j in range(2):\n",
        "    line.append(0)\n",
        "  a.append(line)\n",
        "\n",
        "print(a)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "5ZvreZ9I9U2y",
        "outputId": "161f1510-abcd-4830-ff1f-d0706df742d8"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[0, 0], [0, 0], [0, 0]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(list(range(0,10,3)))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "-FZeDO7r9WP3",
        "outputId": "dae8a409-13ec-4b23-b0d5-3b2b02288e45"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[0, 3, 6, 9]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(list(range(10,0,-3)))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "G6IIoxQu9Yfx",
        "outputId": "c9ab422e-f160-4c9d-ec72-a2deac98eb9d"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[10, 7, 4, 1]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for i in range(10, 0, -3):\n",
        "  print(i)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "flcuaxnN9bTr",
        "outputId": "2be772d3-e152-4fc5-e519-113d6b51949b"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "10\n",
            "7\n",
            "4\n",
            "1\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = ['Alice','Bob','Charlie']\n",
        "\n",
        "for name in a:\n",
        "  print(name)\n",
        "\n",
        "for i, name in enumerate(a):\n",
        "  print(i, name)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "8_sMloZ8-Ogo",
        "outputId": "68bb161c-97cb-4e8b-ed9e-24fd35daa2df"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Alice\n",
            "Bob\n",
            "Charlie\n",
            "0 Alice\n",
            "1 Bob\n",
            "2 Charlie\n"
          ]
        }
      ]
    }
  ]
}
